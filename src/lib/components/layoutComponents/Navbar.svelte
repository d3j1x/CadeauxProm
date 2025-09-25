<script lang="ts">
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, DarkMode, MegaMenu } from "flowbite-svelte";
    import cpromlogo from '$lib/images/logos/cprom-transparent.png';

    import { Drawer, CardPlaceholder, Button, Sidebar, SidebarWrapper, SidebarDropdownWrapper, SidebarGroup, SidebarItem } from "flowbite-svelte";
    import { ChartPieSolid, CartSolid, GridSolid, MailBoxSolid, UsersSolid, ShoppingBagSolid, ArrowRightToBracketOutline, EditOutline } from "flowbite-svelte-icons";
    import { ChevronDownOutline } from "flowbite-svelte-icons";

    let open2 = $state(false);
    let spanClass = "flex-1 ms-3 whitespace-nowrap";

    // close drawer
    function closeDrawer() {
      open2 = false;
    }

    let menu = [
    { name: "Tableaux", href: "/" },
    { name: "Montres", href: "/" },
    { name: "Autres..", href: "/" }
  ];
</script>

<Navbar class="  px-2 sm:px-4 sm:py-2 rounded shadow-md ">
  
  <NavBrand href="/">
    <img src={cpromlogo} class="me-3 h-6 h-9 dark:invert" alt="Cadeaux Prom Logo" />
    <span class="self-center text-xl md:text-2xl font-semibold whitespace-nowrap dark:text-white">Cadeaux Prom</span>
  </NavBrand>
  
  <div class="flex md:order-2">
    <DarkMode />
    <Button color="alternative" pill onclick={() => (open2 = true)} class="md:hidden p-2 ml-2 rounded-md border-none ">
      <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
      <path stroke="currentColor" stroke-linecap="round" stroke-width="2" d="M5 7h14M5 12h14M5 17h14"/>
      </svg>
    </Button> 
  </div>

  <NavUl class="order-1">
    <NavLi class="text-lg" href="/">Accueil</NavLi>
    <NavLi class="text-lg lg:mx-4" href="/">Cadeaux</NavLi>
    <NavLi class="text-lg" href="/">Packs</NavLi>
    <NavLi class="text-lg  lg:mx-4" href="/">Articles</NavLi>
    <NavLi class="cursor-pointer  text-lg" onclick={() => (open = true)}>
      Decorative<ChevronDownOutline class="text-primary-800 ms-2 inline h-6 w-6  text-lg" />
    </NavLi>
    <MegaMenu items={menu} >
      {#snippet children({ item })}
        <a href={item.href} class="hover:text-primary-600 dark:hover:text-primary-500 mx-2">{item.name}</a>
      {/snippet}
    </MegaMenu>
  </NavUl>
</Navbar>

<Drawer bind:open={open2} class="w-64 bg-gray-50 p-0 dark:bg-gray-800">
  
  <Sidebar disableBreakpoints={true} class="top-16">
    <SidebarWrapper class="overflow-y-auto rounded-sm px-3 py-0 dark:bg-gray-800">
      <SidebarGroup>
        <SidebarItem label="Accueil"  href="/" onclick={closeDrawer}>
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m4 12 8-8 8 8M6 10.5V19a1 1 0 0 0 1 1h3v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h3a1 1 0 0 0 1-1v-8.5"/>
            </svg>
          {/snippet}
        </SidebarItem>
        <SidebarDropdownWrapper label="Cadeaux">
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21v-9m3-4H7.5a2.5 2.5 0 1 1 0-5c1.5 0 2.875 1.25 3.875 2.5M14 21v-9m-9 0h14v8a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-8ZM4 8h16a1 1 0 0 1 1 1v3H3V9a1 1 0 0 1 1-1Zm12.155-5c-3 0-5.5 5-5.5 5h5.5a2.5 2.5 0 0 0 0-5Z"/>
            </svg>
          {/snippet}
          <SidebarItem label="Mariage" href="/" onclick={closeDrawer}/>
          <SidebarItem label="Anniversaire" href="/" onclick={closeDrawer}/>
          <SidebarItem label="Graduation" href="/" onclick={closeDrawer}/>
        </SidebarDropdownWrapper>
        <SidebarItem label="Packs" {spanClass} href="/" onclick={closeDrawer}>
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 13h3.439a.991.991 0 0 1 .908.6 3.978 3.978 0 0 0 7.306 0 .99.99 0 0 1 .908-.6H20M4 13v6a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-6M4 13l2-9h12l2 9M9 7h6m-7 3h8"/>
            </svg>
          {/snippet}
          {#snippet subtext()}
            <span class="ms-3 inline-flex items-center justify-center rounded-full bg-gray-200 px-2 text-sm font-medium text-gray-800 dark:bg-gray-700 dark:text-gray-300">Promo</span>
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Articles" {spanClass} href="/" onclick={closeDrawer}>
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 10V6a3 3 0 0 1 3-3v0a3 3 0 0 1 3 3v4m3-2 .917 11.923A1 1 0 0 1 17.92 21H6.08a1 1 0 0 1-.997-1.077L6 8h12Z"/>
            </svg>
          {/snippet}
          {#snippet subtext()}
            <span class="text-gray-800 bg-gray-200 dark:bg-gray-700 dark:text-gray-300 ms-3 inline-flex h-3 w-3 items-center justify-center rounded-full p-4 text-sm font-medium">+20</span>
          {/snippet}
        </SidebarItem>
        <SidebarDropdownWrapper label="Decorative">
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m7.171 12.906-2.153 6.411 2.672-.89 1.568 2.34 1.825-5.183m5.73-2.678 2.154 6.411-2.673-.89-1.568 2.34-1.825-5.183M9.165 4.3c.58.068 1.153-.17 1.515-.628a1.681 1.681 0 0 1 2.64 0 1.68 1.68 0 0 0 1.515.628 1.681 1.681 0 0 1 1.866 1.866c-.068.58.17 1.154.628 1.516a1.681 1.681 0 0 1 0 2.639 1.682 1.682 0 0 0-.628 1.515 1.681 1.681 0 0 1-1.866 1.866 1.681 1.681 0 0 0-1.516.628 1.681 1.681 0 0 1-2.639 0 1.681 1.681 0 0 0-1.515-.628 1.681 1.681 0 0 1-1.867-1.866 1.681 1.681 0 0 0-.627-1.515 1.681 1.681 0 0 1 0-2.64c.458-.361.696-.935.627-1.515A1.681 1.681 0 0 1 9.165 4.3ZM14 9a2 2 0 1 1-4 0 2 2 0 0 1 4 0Z"/>
</svg>

          {/snippet}
          <SidebarItem label="Tableaux" href="/" onclick={closeDrawer}/>
          <SidebarItem label="Montres" href="/" onclick={closeDrawer}/>
          <SidebarItem label="Autres.." href="/" onclick={closeDrawer}/>
        </SidebarDropdownWrapper>
        <SidebarItem label="Contactez-nous" href="/contactez-nous" onclick={closeDrawer}>
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 13a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"/>
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.8 13.938h-.011a7 7 0 1 0-11.464.144h-.016l.14.171c.1.127.2.251.3.371L12 21l5.13-6.248c.194-.209.374-.429.54-.659l.13-.155Z"/>
            </svg>
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Facebook" href="https://www.facebook.com/profile.php?id=100066795998795" target="_blank" onclick={closeDrawer}>
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M13.135 6H15V3h-1.865a4.147 4.147 0 0 0-4.142 4.142V9H7v3h2v9.938h3V12h2.021l.592-3H12V6.591A.6.6 0 0 1 12.592 6h.543Z" clip-rule="evenodd"/>
            </svg>
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Instagram" href="https://www.instagram.com/cadeaux_prom/" target="_blank" onclick={closeDrawer}>
          {#snippet icon()}
            <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path fill="currentColor" fill-rule="evenodd" d="M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V8Zm5-3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H8Zm7.597 2.214a1 1 0 0 1 1-1h.01a1 1 0 1 1 0 2h-.01a1 1 0 0 1-1-1ZM12 9a3 3 0 1 0 0 6 3 3 0 0 0 0-6Zm-5 3a5 5 0 1 1 10 0 5 5 0 0 1-10 0Z" clip-rule="evenodd"/>
            </svg>
          {/snippet}
        </SidebarItem>
      </SidebarGroup>
    </SidebarWrapper>
  </Sidebar>
</Drawer>
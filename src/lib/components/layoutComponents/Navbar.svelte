<script lang="ts">
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, DarkMode } from "flowbite-svelte";
    import cpromlogo from '$lib/images/logos/cprom-transparent.png';

    import { Drawer, CardPlaceholder, Button, Sidebar, SidebarWrapper, SidebarDropdownWrapper, SidebarGroup, SidebarItem } from "flowbite-svelte";
    import { ChartPieSolid, CartSolid, GridSolid, MailBoxSolid, UsersSolid, ShoppingBagSolid, ArrowRightToBracketOutline, EditOutline } from "flowbite-svelte-icons";
    let open2 = $state(false);
    let spanClass = "flex-1 ms-3 whitespace-nowrap";
</script>

<Navbar class=" border-gray-200 px-2 sm:px-4 py-2.5 rounded shadow-md ">
  
  <NavBrand href="/">
    <img src={cpromlogo} class="me-3 h-6 sm:h-9 dark:invert" alt="Cadeaux Prom Logo" />
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
    <NavLi class="text-lg mx-2" href="/about">À propos</NavLi>
    <NavLi class="text-lg mr-2" href="/docs/components/navbar">Packs</NavLi>
    <NavLi class="text-lg mr-2" href="/pricing">Produits</NavLi>
    <NavLi class="text-lg" href="/contact">Contact</NavLi>
  </NavUl>
</Navbar>

<Drawer bind:open={open2} class="w-64 bg-gray-50 p-0 dark:bg-gray-800">
  <h5 class="px-6 py-4 text-base font-semibold text-gray-500 uppercase dark:text-gray-400">Menu</h5>
  <Sidebar disableBreakpoints={true} class="top-16">
    <SidebarWrapper class="overflow-y-auto rounded-sm px-3 py-0 dark:bg-gray-800">
      <SidebarGroup>
        <SidebarItem label="Dashboard">
          {#snippet icon()}
            <ChartPieSolid class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
        </SidebarItem>
        <SidebarDropdownWrapper label="E-commerce">
          {#snippet icon()}
            <CartSolid class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
          <SidebarItem label="Products" />
          <SidebarItem label="Billing" />
          <SidebarItem label="Invoice" />
        </SidebarDropdownWrapper>
        <SidebarItem label="Kanban" {spanClass}>
          {#snippet icon()}
            <GridSolid class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
          {#snippet subtext()}
            <span class="ms-3 inline-flex items-center justify-center rounded-full bg-gray-200 px-2 text-sm font-medium text-gray-800 dark:bg-gray-700 dark:text-gray-300">Pro</span>
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Inbox" {spanClass}>
          {#snippet icon()}
            <MailBoxSolid class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
          {#snippet subtext()}
            <span class="text-primary-600 bg-primary-200 dark:bg-primary-900 dark:text-primary-200 ms-3 inline-flex h-3 w-3 items-center justify-center rounded-full p-3 text-sm font-medium">3</span>
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Users">
          {#snippet icon()}
            <UsersSolid class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Products">
          {#snippet icon()}
            <ShoppingBagSolid class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Sign In">
          {#snippet icon()}
            <ArrowRightToBracketOutline class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
        </SidebarItem>
        <SidebarItem label="Sign Up">
          {#snippet icon()}
            <EditOutline class="h-5 w-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:text-gray-400 dark:group-hover:text-white" />
          {/snippet}
        </SidebarItem>
      </SidebarGroup>
    </SidebarWrapper>
  </Sidebar>
</Drawer>
<script lang="ts">

  import { 
        Nav,
        Navbar, 
        NavItem, 
        NavLink, 
        NavbarBrand
  } from 'sveltestrap';

</script>
  <Navbar color="light" light expand="md">
    <NavbarBrand href="https://github.com/KorieDrakeChaney">KorieDrakeChaney</NavbarBrand>
    <Nav tabs class="ms-auto" navbar>
        <NavItem>
            <NavLink href="/Blogs">Blogs</NavLink>
          </NavItem>
          <NavItem>
            <NavLink href="/About">About</NavLink>
          </NavItem>
          <NavItem>
            <NavLink href="/Portfolio">Portfolio</NavLink>
          </NavItem>
    </Nav>
  </Navbar>
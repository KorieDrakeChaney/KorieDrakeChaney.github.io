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
        <NavLink href="/">Home</NavLink>
      </NavItem>
        <NavItem>
            <NavLink href="/blogs">Blogs</NavLink>
          </NavItem>
          <NavItem>
            <NavLink href="/about">About</NavLink>
          </NavItem>
          <NavItem>
            <NavLink href="/portfolio">Portfolio</NavLink>
          </NavItem>
    </Nav>
  </Navbar>
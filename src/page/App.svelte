<script>
  import Layout from "../layout/Layout.svelte";
  import "./social-icons.scss";

  import Discord from "./assets/Discord.png";
  import X from "./assets/X.png";
  import Avatar from "./assets/_avatar.webp";
</script>

<div id="background" />

<Layout>
  <div id="content-container">
    <div id="content">
      <img
        src={Avatar}
        alt="User Avatar"
        class="avatar"
        width="100px"
        height="100px"
      />
      <h2>Razor</h2>
      <div class="social-icon-wrapper">
        <div class="social-icon-container">
          <a href="https://x.com/chuuyatimezones" target="_blank">
            <img
              src={X}
              width={20}
              height={20}
              alt="X"
              class="social-icon with-push"
            />
          </a>
          <a
            href="https://discord.com/users/1131734127113162873"
            target="_blank"
          >
            <img
              src={Discord}
              width={25}
              height={20}
              alt="Discord"
              class="social-icon with-push"
            />
          </a>
        </div>
      </div>
    </div>
    <a class="credit" href="https://myferr.foo.ng" target="_blank"
      >created by myferr</a
    >
  </div>
</Layout>

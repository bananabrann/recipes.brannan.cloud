<script>
  import "../app.css";
  import Navbar from "../components/Navbar.svelte";
</script>

<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Recipes</title>
  <link rel="stylesheet" href="https://use.typekit.net/xtr6jqc.css" />
</head>

<main>
  <Navbar />
  <slot />
</main>

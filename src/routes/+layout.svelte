<script lang="ts">
    import type { LayoutData } from './$types';
    
    export let data: LayoutData;
    const d = data;
</script>


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
    <title>Home - Brand</title>
    <link rel="stylesheet" href="assets/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,700,300italic,400italic,700italic&amp;display=swap">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Alegreya+Sans+SC&amp;display=swap">
    <link rel="stylesheet" href="assets/fonts/fontawesome-all.min.css">
    <link rel="stylesheet" href="assets/fonts/font-awesome.min.css">
    <link rel="stylesheet" href="assets/fonts/fontawesome5-overrides.min.css">
    <link rel="stylesheet" href="assets/css/animations.compiled.css">
    <link rel="stylesheet" href="assets/css/Articles-Cards.css">
    <link rel="stylesheet" href="assets/css/Footer-Clean.css">
    <link rel="stylesheet" href="assets/css/main.css">
    <link rel="stylesheet" href="assets/css/nav-styling.css">
</head>

<body id="page-top" style="background: var(--bs-body-color);font-family: 'Source Sans Pro', sans-serif;">

<slot />

<script type="module" src="assets/bootstrap/js/bootstrap.min.js"></script>
<script src="assets/js/stylish-portfolio.js"></script>
</body>

</html>
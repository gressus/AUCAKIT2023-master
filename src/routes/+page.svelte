
<section class="s1"> 
    test 1. No background image displayed in the built project.
</section>
<section class="s2"> 
    test 2
</section>
<section style="min-height: 100vh;width: 100%;background-image: url('2.jpg') !important;background-position: center;background-size: cover;position: relative;"> 
    test 3
</section>

<ul><li>No image displayed in the built project.</li></ul>

<style>
.s1 {
    min-height: 100vh;
    width: 100%;
    background-image: url('2.jpg') !important;
    background-position: center;
    background-size: cover;
    position: relative;    
}

.s2 {
    min-height: 100vh;
    width: 100%;
    background-image: url('/2.jpg') !important;
    background-position: center;
    background-size: cover;
    position: relative;
}

li {
  list-style-image: url('favicon.png');
}
</style>
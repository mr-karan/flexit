<template>
    <section>
    <header class="grid-header text-center">
        <h1>Flexit</h1>
        <h2>Simple, clean and no fuss flexbox based grid</h2>
    </header>
    <div id="app" class="container">
        <div class="row">
            <div class="one columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
            <div class="five columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
            <div class="six columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="four columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
            <div class="five columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
            <div class="three columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="columns">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
            <div class="one column">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
            <div class="one column">
                <div class="box-column">
                <p>Columns</p>
                </div>
            </div>
        </div>
    </div>
    </section>
</template>

<script>
export default {
  name: 'App'
}
</script>

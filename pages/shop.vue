<template>
    <div>
        <BlockHeaderPlain title="Shop">
            <template v-slot:side-content>
            </template>
        </BlockHeaderPlain>
          <div id="shop">The JupyterCon shop is loading...</div>
        <DesktopFooter />
    </div>
</template>

<script>
    import BlockHeaderPlain from "../components/BlockHeaderPlain";
    import DesktopFooter from "../components/DesktopFooter";

    export default {
        name: "shop",
        components: {DesktopFooter, BlockHeaderPlain},
    }
</script>

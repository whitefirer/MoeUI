<template>
    <div>
        <div>
            <h2>Basic Buttons</h2>
            <moe-button type="default">Default</moe-button>
            <moe-button type="primary">Primary</moe-button>
            <moe-button type="comfy">Comfy</moe-button>
            <moe-button type="remindful">Remindful</moe-button>
            <moe-button type="violent">Violent</moe-button>
            <moe-button type="clean">Clean</moe-button>
        </div>
        <div>
            <h2>Disabled</h2>
            <moe-button type="default" disabled>disabled</moe-button>
        </div>
        <div>
            <h2>Special Buttons - Default</h2>
            <moe-button icon="heart" type="default">/// 好き ///</moe-button>
            <moe-button icon="star" type="default">> マーク <</moe-button>
        </div>
        <div>
            <h2>Button Group</h2>
            <moe-button-group>
                <moe-button type="default"><- Prev</moe-button>
                <moe-button type="default">1</moe-button>
                <moe-button type="default">2</moe-button>
                <moe-button type="default">3</moe-button>
                <moe-button type="default">4</moe-button>
                <moe-button type="default">Next -></moe-button>
            </moe-button-group>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">

</style>

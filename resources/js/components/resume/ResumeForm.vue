<template>
    <div>
        <div>
            <Tabs>
                <Tab title="Test" icon="fas fa-user">
                    <h1>Test primero</h1>
                </Tab>
                <Tab title="otro" icon="fas fa-user">
                    <h1>Test dos</h1>
                </Tab>
            </Tabs>
        </div>
    </div>
</template>

<script>
import Tabs from "./tabs/Tabs";
import Tab from "./tabs/Tab";
export default {
    name: "ResumeForm",

    components: {
        Tabs,
        Tab
    }
};
</script>

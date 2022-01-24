<script context="module">
    export async function load() {
        const today = new Date()
        return {
            status: 302,
            redirect: `/${today.getFullYear()}-${today.getMonth() + 1}-${today.getDate()}`
        };
    }
</script>
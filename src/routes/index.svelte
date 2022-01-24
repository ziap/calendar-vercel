<script context="module">
    export async function load() {
        const today = new Date()
        return {
            status: 302,
            redirect: `/${today.getMonth() + 1}-${today.getDate()}-${today.getFullYear()}`
        };
    }
</script>
<template>
    <header>
        <div>
            <svg viewBox="0 0 24 24" aria-hidden="true" height="30" fill="rgb(29, 155, 240)">
                <g>
                    <path
                        d="M23.643 4.937c-.835.37-1.732.62-2.675.733.962-.576 1.7-1.49 2.048-2.578-.9.534-1.897.922-2.958 1.13-.85-.904-2.06-1.47-3.4-1.47-2.572 0-4.658 2.086-4.658 4.66 0 .364.042.718.12 1.06-3.873-.195-7.304-2.05-9.602-4.868-.4.69-.63 1.49-.63 2.342 0 1.616.823 3.043 2.072 3.878-.764-.025-1.482-.234-2.11-.583v.06c0 2.257 1.605 4.14 3.737 4.568-.392.106-.803.162-1.227.162-.3 0-.593-.028-.877-.082.593 1.85 2.313 3.198 4.352 3.234-1.595 1.25-3.604 1.995-5.786 1.995-.376 0-.747-.022-1.112-.065 2.062 1.323 4.51 2.093 7.14 2.093 8.57 0 13.255-7.098 13.255-13.254 0-.2-.005-.402-.014-.602.91-.658 1.7-1.477 2.323-2.41z">
                    </path>
                </g>
            </svg>
        </div>
        <div class="searchContainer">
            <svg viewBox="0 0 24 24" aria-hidden="true"
                class="logo">
                <g>
                    <path
                        d="M10.25 3.75c-3.59 0-6.5 2.91-6.5 6.5s2.91 6.5 6.5 6.5c1.795 0 3.419-.726 4.596-1.904 1.178-1.177 1.904-2.801 1.904-4.596 0-3.59-2.91-6.5-6.5-6.5zm-8.5 6.5c0-4.694 3.806-8.5 8.5-8.5s8.5 3.806 8.5 8.5c0 1.986-.682 3.815-1.824 5.262l4.781 4.781-1.414 1.414-4.781-4.781c-1.447 1.142-3.276 1.824-5.262 1.824-4.694 0-8.5-3.806-8.5-8.5z">
                    </path>
                </g>
            </svg>
            <input placeholder="Search" />
        </div>
    </header>
</template>
  
<script>
export default {
    name: 'TopBar',
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
    display: flex;
    flex-direction: row;
    align-items:center;
    width: 100%;
    box-sizing: border-box;
    flex-shrink: 0;
    position: sticky;
    z-index: 1100;
    top: 0px;
    left: auto;
    right: 0px;
    padding: 5px;
    transition: width 300ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
    box-shadow: none;
    backdrop-filter: blur(20px);
    border-style: solid;
    border-color: rgb(231, 235, 240);
    border-width: 0px 0px thin;
    background: rgba(255, 255, 255, 0.7);
    color: rgb(45, 56, 67);
}

.searchContainer {
    flex: 1;
    text-align: center;
}
.logo{
    height: 24px;
    position: absolute;
    top: 0;
    bottom: 0;
    transform: translate(51%, 63%);
}
input {
    width: 50%;
    padding: 13px;
    border-radius: 26px;
    border: 1px solid #cdcdcd;
    background: #f6f6f6;
    padding-left: 41px;

}
</style>
  
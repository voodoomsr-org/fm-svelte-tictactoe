<script>
    import appIconFile from '$lib/images/tictactoe/appIcon.svg';
    import PlayerPicker from './PlayerPicker.svelte';
</script>

<div id="container">
    <div id="appIcon">
        <img src={appIconFile} alt=""/>
    </div>
    <PlayerPicker />
    <div id="buttonsStrip">BUTTONS</div>
</div>

<style>

    #container {
        background-color: #1F3641;
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 28.75rem;
        gap: 2.5rem;
    }

    div {
        border: 1px solid black;
    }

    #appIcon {
        height: 2rem;
        width: 4.5rem;
    }

    #buttonsStrip {
        height: 9.625rem;
        width: 100%;
    }

</style>

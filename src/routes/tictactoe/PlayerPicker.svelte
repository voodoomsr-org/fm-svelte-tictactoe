<script>
    import Picker from "./Picker.svelte";
</script>

<div id="playerPicker" class="font">
    <div id="message" class="silver">PICK PLAYER 1’S MARK</div>
    <div id="selector">
        <Picker/>
        <Picker/>
    </div>
    <div id="message2" class="silver opacity">REMEMBER : X GOES FIRST</div>
</div>

<style>
    .font {
        font-family: 'Outfit', sans-serif;
    }

    .silver {
        color: #A8BFC9;
    }

    .opacity {
        opacity: 50%;
    }

    div {
        border: 1px solid green;
        box-sizing: border-box;
    }

    #message {
        margin-bottom: 1.5rem;
    }

    #playerPicker {
        height: 12.8125rem;
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 1.5rem;
        padding-bottom: 1.5rem;
        box-shadow: 0px -0.5rem #10212A inset;
        border-radius: 1rem;
    }

    #selector {
        width: 25.75rem;
        height: 4.5rem;
        background-color: #1A2A33;
        border-radius: .625rem;
        margin-bottom: 1.0625rem;
        display:flex;
        align-items: center;
        justify-content: center;
    }

</style>
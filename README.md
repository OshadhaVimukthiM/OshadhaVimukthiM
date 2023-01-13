<style>
    .subscribe-button {
        background-color: rgb(200, 0, 0);
        color: white;
        border: none;
        margin-left: 20px;
        margin-right: 8px;
        padding-top: 10px;
        padding-bottom: 10px;
        padding-left: 16px;
        padding-right: 16px;
        border-radius: 2px;
        cursor: pointer;
        vertical-align: top;
        transition: opacity 0.15s;
    }

    .subscribe-button:hover {
        opacity: 0.8;
    }

    .subscribe-button:active {
        opacity: 0.5;
    }

    .join-button {
        background-color: white;
        border-color: rgb(41, 118, 211);
        border-style: solid;
        border-width: 1px;
        color: rgb(41, 118, 211);
        margin-right: 8px;
        padding-top: 9px;
        padding-bottom: 9px;
        padding-left: 16px;
        padding-right: 16px;
        border-radius: 2px;
        cursor: pointer;
        vertical-align: top;
        transition: background-color 0.15s,
         color 0.15s;
    }

    .join-button:hover {
        background-color: rgb(41, 118, 211);
        color: white;
    }

    .join-button:active {
        opacity: 0.7;
    }

    .tweet-button {
        background-color: rgb(2, 158, 255);
        color: white;
        border: none;
        padding-top: 9px;
        padding-bottom: 9px;
        padding-left: 16px;
        padding-right: 16px;
        border-radius: 18px;
        font-weight: bold;
        font-size: 15px;
        cursor: pointer;
        margin-right: 8px;
        vertical-align: top;
        transition: box-shadow 0.15s;
    }

    .tweet-button:hover {
        box-shadow: 3px 5px 5px rgba(0, 0, 0, 0.18);
    }
</style>

<button class="subscribe-button">
    SUBSCRIBE
</button>

<button class="join-button">
    JOIN
</button>

<button class="tweet-button">
    Tweet
</button>

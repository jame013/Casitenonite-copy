<script>
    let q = {
        q1: "question 1",
    };
    let choice = { c1: "choice 1", c2: "choice2" };
    // let circle = "bg-gray-300"
    let bg_c1 = "bg-white";
    let bg_c2 = "bg-black";
    let count = 1;
    let flag1 = false;
    let flag2 = false;

    let bon1 = false;
    let bon2 = true;
    const nextPage = () => {
        setTimeout(() => {
            count++;
            flag1 = false;
            flag2 = false;
        }, 500);
    };
</script>

<body class="text-sm bg-cover overflow-hidden h-screen" style="background-image: url('img/bgeiei.jpg');">
    <nav class="w-[900px] mx-auto backdrop-blur sticky top-5">
        <ul class=" flex justify-center items-center py-2 gap-28 text-white text-2xl">
            <a href="/">Home</a>
            <a href="/game">Game</a>
            <a href="/lastest">Lastest</a>
        </ul>
    </nav>

    <div class=" items-center m-auto flex justify-center">
        <img class="w-100 h-100" src="img/end.png" alt="" />
    </div>
</body>


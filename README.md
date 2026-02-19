# football-ground-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Football Academy</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background:#f4f4f4;
}

/* HEADER */
.header{
    height:90vh;
    background:url("https://images.unsplash.com/photo-1508098682722-e99c43a406b2") no-repeat center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    text-align:center;
}

.header h1{
    font-size:50px;
}

.header span{
    color:#ff3c3c;
}

/* SECTION */
.section{
    padding:60px 10%;
    background:white;
}

.row{
    display:flex;
    gap:40px;
    align-items:center;
}

.row img{
    width:350px;
    border-radius:10px;
}

.row-text h2{
    margin-bottom:15px;
}

/* BLACK QUOTE SECTION */
.quote{
    background:black;
    color:white;
    text-align:center;
    padding:40px;
    font-size:20px;
}

.quote span{
    color:#ff3c3c;
}

/* COACH SECTION */
.coaches{
    padding:60px 10%;
    background:#f4f4f4;
}

.coach{
    display:flex;
    align-items:center;
    gap:30px;
    margin-bottom:40px;
}

.coach img{
    width:150px;
    height:150px;
    border-radius:50%;
    object-fit:cover;
}

/* PLAYER SECTION */
.player{
    background:#c62828;
    color:white;
    padding:60px 10%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.player img{
    width:300px;
}

/* GALLERY */
.gallery{
    padding:60px 10%;
    background:white;
}

.gallery-images{
    display:flex;
    gap:20px;
}

.gallery-images img{
    width:33%;
    border-radius:10px;
}

/* JOIN FORM */
.join{
    padding:60px 10%;
    background:#f4f4f4;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.join form{
    display:flex;
    flex-direction:column;
    gap:15px;
    width:40%;
}

.join input{
    padding:10px;
    border-radius:20px;
    border:1px solid #ccc;
}

.join button{
    padding:10px;
    background:#c62828;
    color:white;
    border:none;
    border-radius:20px;
    cursor:pointer;
}

.join img{
    width:250px;
}
</style>

</head>
<body>

<!-- HEADER -->
<div class="header">
    <h1>TRAIN LIKE A <span>CHAMP</span></h1>
</div>

<!-- ABOUT -->
<div class="section">
    <div class="row">
        <img src="https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a">
        <div class="row-text">
            <h2>Founding of the Football Academy</h2>
            <p>Our academy trains young players with professional coaching and modern facilities. 
            We build skills, teamwork, and winning mindset.</p>
        </div>
    </div>
</div>

<!-- QUOTE -->
<div class="quote">
    NEVER LET THE <span>FEAR</span> OF LOSING KEEP YOU FROM <span>WINNING</span> THE GAME
</div>

<!-- COACHES -->
<div class="coaches">
    <div class="coach">
        <img src="https://randomuser.me/api/portraits/men/32.jpg">
        <div>
            <h3>Ian Pantucek</h3>
            <p>Head Coach</p>
        </div>
    </div>

    <div class="coach">
        <img src="https://randomuser.me/api/portraits/men/45.jpg">
        <div>
            <h3>Oliver Wahn</h3>
            <p>Assistant Coach</p>
        </div>
    </div>

    <div class="coach">
        <img src="https://randomuser.me/api/portraits/men/12.jpg">
        <div>
            <h3>Brandon Hulk</h3>
            <p>Life Coach</p>
        </div>
    </div>
</div>

<!-- PLAYER -->
<div class="player">
    <div>
        <h2>Player of the Week</h2>
        <h1>Johan Brandy</h1>
        <p>10 Goals | 5 Assists</p>
    </div>
    <img src="https://images.unsplash.com/photo-1521412644187-c49fa049e84d">
</div>

<!-- GALLERY -->
<div class="gallery">
    <h2>Gallery</h2>
    <div class="gallery-images">
        <img src="https://images.unsplash.com/photo-1517466787929-bc90951d0974">
        <img src="https://images.unsplash.com/photo-1508804185872-d7badad00f7d">
        <img src="https://images.unsplash.com/photo-1471295253337-3ceaaedca402">
    </div>
</div>

<!-- JOIN -->
<div class="join">
    <form>
        <h2>Join The Team!</h2>
        <input type="text" placeholder="Name">
        <input type="email" placeholder="Email">
        <input type="number" placeholder="Age">
        <input type="text" placeholder="Phone Number">
        <button type="submit">Submit</button>
    </form>
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Soccerball.svg">
</div>

</body>
</html>

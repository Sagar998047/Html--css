*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    box-sizing: border-box;
}

body{
    background:linear-gradient(to right, rgba(248, 13, 142,1), rgba(248, 232, 89,1));
}

h1{
    
    color: white;
    padding: 20px;

}

nav{
    background-color: white;
    display: grid;
    place-items: center;
}

nav ul{
    list-style-type: none;
}

nav ul a{
    display: inline-block;
    padding: 20px;
    text-decoration: none;
    color: black;
    font-weight: bold;
    transition: 0.2s ease-in;
}

#image{
    background:linear-gradient(to right, rgb(250, 33, 124), rgb(247, 163, 6)); 
    height: 100%;
    width: 100%;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

#image{
    background-image: url("food-table.jpg");
}

#content{
    display: block;
    align-items: center;
    justify-content: center;
    height: 450px;
    width :30%;
    padding-top: 150px;
    margin-left: 80px;
    margin-bottom: 100px;
    color: white;
}

hr{
    height: 15px;
    background-color: white;
}

.items{
    display: grid;
    grid-template-columns: repeat(3,1fr);
    padding: 30px 20px;
    grid-column-gap: 20px;
    grid-row-gap: 30px;
    height: 280px;
}

.item{
width: 270px;
box-sizing: border-box;
text-align: center;
border-radius: 0 40px ;
cursor: pointer;
padding:15px;
display: inline-block;
justify-content: space-between;
align-items: center;
box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
transition: 0.4s;
background-color:#f2f2f2 ;
height: 350px;
margin-left: 80px;
}

.item img{
    width: 100%;
    object-fit: cover;
    cursor: pointer;
    transition: 0.2s ease;

    height: 250px;
    border-radius: 0 40px ;
}

.item h5{
    padding: 5px;
    text-align: center;
}

button{
    padding: 10px 50px;
    border: none;
    outline: none;
    border-radius: 20px;
    background-color: rgb(243, 168, 185);
    font-size:18px;
    font-weight: bold;
    display: block;
    margin: 0 auto;
}

.phone-icon, .cart-icon{
    text-decoration: none;
    color: #333;
    font-size: 20px;
    margin-left: 10px;
}

@media screen and (max-width:1000px){
    .items{
        grid-template-columns: repeat(2,1fr);
    }   
}

@media screen and (max-width:400px){
    .items{
        grid-template-columns: repeat(1,1fr);
    }   
}

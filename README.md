# Project 0

Web Programming with Python and JavaScript




#main-section {
    margin-top:100px;
    min-height:600px;
    color:$tertiary-color;
    background-image: url('../Images/web4.jpg');
    background-position: center center;
    background-repeat: no-repeat;     

    & .container{
        margin:auto;
        width:100%;
        min-height: 600px;
        text-align: center;
        padding: 100px 10px;
        background-color:rgba(0, 0, 0, 0.01);
    }
    & h1{
        font-size:40px;
        padding: 20px 0px;
        color:$primary-color;
    }
    & p{
        font-size:25px;
        padding :0px 40px;
        text-align: justify; 
    }
}

#side{
    margin: 100px 0px;

    &.container{
        display:grid;
        grid-template-columns: repeat(3,1fr);
        
    }
}
#side h3{
    text-align:center;
    font-size: 20px; 
}    
#side .box{
    margin: 10px;
    text-align:justify;
    line-height: 40px;
    width:31%
}

#side-bar{
    float:right;
    width: 30%;
    margin-top: 20px;
}
#blog{
    width:80%;
    margin:auto;

    & img{
        margin-top:100px;
        width:100%;
        height: 400px;
    }
    & h3{
        font-size: 2em;
        color:$primary-color;
        margin: 20px 0px 10px;
    }
    & small {
        font-style: italic;
        font-size: 1.2em;
    }
    & p{
        margin-top:10px;
        text-align: justify;
        font-size: 1.2em;
        color:$font-color;
        padding-bottom: 10px;
        border-bottom: 1px solid $secondary-color;
    }
}
#about{
    float: left;
    width:60%;
    margin: 20px 20px 200px 20px;
    
    & h2{
        color:$primary-color;
        padding-bottom: 10px;
        font-size:25px;
    }
    
    & p{
        text-align:justify;
        line-height: 1.5em;
        font-size:20px;
    }    
}
.dark{
    background-color: $primary-color;
    color:$tertiary-color;
    padding: 20px;
    margin-right: 20px;

    & h2{
        padding-bottom: 10px;
        font-size:25px;
    }
    
    & p{
        text-align:justify;
        line-height: 1.5em;
        font-size:20px;
    }
    
}
#space{
    margin-top:100px;
    margin-bottom:100px;
}

#services{
    font-family: $font;
    
    text-align:justify;
    line-height: 1.5em;
    font-size:20px;
    width:60%;
    margin: 100px auto;  
    padding: 20px;
    
    & h2{
        text-align: center;
        background-image:url('../Images/Web2.jpg');
        background-position: center center;
        padding:10px 0px;
        color:$tertiary-color;
    }

    & h3{
        color:$primary-color;
        padding: 20px 0px 10px;
        border-bottom: 1px solid $secondary-color;
    }
    & p{
        padding: 10px;
    }
}
#form{
    background:url('../Images/Web3.jpg');
    background-position: center center;
    margin:-100px 0px -200px;
    z-index: -1;
}
    
table{
    width: 100%;
    background-color:$primary-color;
    color: $tertiary-color;
    min-height:200px;
    border-top:2px $primary-color solid;

    & a{
        color:$tertiary-color;
        text-decoration:none;

        &:hover{
            text-decoration: underline;
        }
    }

    td{
        text-align:left;
}

    .lc{
        padding-left: 70px;
    }
}

#main-footer{
    background-color: $primary-color;
    color:$tertiary-color;
    
    padding: 50px;
    text-align: center;

    & p{
        padding-left:10px;
    }
    
}

@import 'media';
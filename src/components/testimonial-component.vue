<template>
    <div class="container">
        <div class="content">
            <div class="cote">
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="25" viewBox="0 0 32 25" fill="none">
                    <path d="M31.7108 0L31.8072 0.191574C29.8795 1.21328 28.3052 2.71392 27.0843 4.69349C25.8635 6.6092 25.253 8.62069 25.253 10.728C25.253 11.0473 25.2851 11.3027 25.3494 11.4943C25.4779 11.622 25.6064 11.7497 25.7349 11.8774C25.9277 11.9413 26.1847 12.0051 26.506 12.069C28.1767 12.3244 29.494 13.0588 30.4578 14.272C31.4859 15.4215 32 16.8263 32 18.4866C32 20.3384 31.3574 21.9029 30.0723 23.1801C28.7872 24.3934 27.1807 25 25.253 25C23.0683 25 21.3012 24.2656 19.9518 22.7969C18.6024 21.3282 17.9277 19.3806 17.9277 16.954C17.9277 13.1226 19.2129 9.57855 21.7831 6.32184C24.3534 3.06514 27.6627 0.957857 31.7108 0ZM13.7831 0L13.8795 0.191574C11.9518 1.21328 10.3775 2.71392 9.15663 4.69349C7.93574 6.6092 7.3253 8.62069 7.3253 10.728C7.3253 11.0473 7.35743 11.3027 7.42169 11.4943C7.5502 11.622 7.67871 11.7497 7.80723 11.8774C8 11.9413 8.25703 12.0051 8.57831 12.069C10.249 12.3244 11.5663 13.0588 12.5301 14.272C13.5582 15.4215 14.0723 16.8263 14.0723 18.4866C14.0723 20.3384 13.4297 21.9029 12.1446 23.1801C10.8594 24.3934 9.25301 25 7.3253 25C5.14056 25 3.37349 24.2656 2.0241 22.7969C0.674699 21.3282 0 19.3806 0 16.954C0 13.1226 1.28514 9.57855 3.85542 6.32184C6.4257 3.06514 9.73494 0.957857 13.7831 0Z" fill="#41EAD4"/>
                </svg>
            </div>
            <div class="body">
                <div>
                    <div class="title m-b-10">
                        Elementum mi felis, sit velit lobortis ultricies non. Mattis enim, nisl
                    </div>
                    <div class="title1">
                        adipiscing natoque diam et. Cum posuere in velit massa sagittis augue egestas. 
                        Eu sollicitudin et quam eu. Nunc, sed imperdiet blandit morbi. 
                        Maecenas lobortis tristique rutrum.
                    </div>
                </div>
                <div class="profile">
                    <div class="mask-group">
                        <img src="../assets/images/mask-group.png">
                    </div>
                    <div class="title-profile">
                        Judy ROSELESS<br>MARKETING HEAD at ROM.
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container{
    width: 510px;
    height: 504px;
    flex-shrink: 0;
    border-radius: 5px;
    background: #02223B;
    box-shadow: 0px 20px 30px 0px rgba(0, 201, 224, 0.03);
    border: 1px solid #02223B;
}
.profile{
    display: flex;
    margin-top: 25px;
    align-items: center;
}
.mask-group > img{
    border-radius: 4px;
    background-blend-mode: multiply, normal;
    margin-right: 12px;
}
.title1{
    color: #FFF;
    font-family: 'Larsseit' sans-serif;
    font-size: 18px;
    font-style: normal;
    font-weight: 300;
    line-height: 190%;
}
.title{
    color: #FFF;
    font-family: 'Larsseit' sans-serif;
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
    line-height: 190%; /* 34.2px */
}
.title-profile{
    color: #FFF;
    font-family: 'Larsseit' sans-serif;
    font-size: 12px;
    font-style: normal;
    font-weight: 700;
    line-height: 170%; /* 20.4px */
    letter-spacing: 1.8px;
    text-transform: uppercase;
}
.cote{
    margin-right: 12px;
}
.content{
    margin: 75px 50px 75px 74px;
    display: flex;
    align-items: flex-start;
}

</style>
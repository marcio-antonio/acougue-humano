

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: none;
  font-family: sans-serif;
  font-size: 14px;
}

body{
  width: 100%;
  min-height: 100vh;
  background-color: rgb(0,0,0);
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
}

.açougueiro-wrapper{
  display: flex;
  align-items: center;
  justify-content: start;
  width: 60%;
  height: 100vh;
}

.açougueiro-phone{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50%;
}

.açougueiro-phone img{
  height: 12.5rem;
}

.açougueiro-continue{
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-direction: column;
  width: 50%;
  min-height: 34rem;
}

.group{
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: column;
  background-color: #8B0000;
  width: 125%;
  padding: 1.3rem 0;
  border: 1px solid lightgray;
}

.group:nth-child(1){
  min-height: 19rem;
}

.açougue-logo{
  height: 9rem;
}

.profile-photo{
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  overflow: hidden;
}

.profile-photo img{
  height: 6rem;
}

.açougue-login{
  background-color: #FA8072;
  color: #000000;
  padding: 8px;
  border-radius: 4px;
}

.açougue-logout{
  color: #000000;
  margin-top: 1rem;
  padding: 8px;
  border-radius: 4px;
  background-color: #FA8072;
}

.not-account{
  margin: 0.5rem;
  color: rgb(0,0,0);
}

.link-black{
  color: #F8F8FF;
}

.get-the-app{
  color: #F8F8FF;
  display: flex;
  width: auto;
}

.download{
  display: grid;

  width: 50%;
}

.app-download{
  height: 3.5rem;
  width: 17.5rem;
  background-size: cover;
}

.app-download:nth-child(1){
  background-image: url("apple-button.png");
}

.app-download:nth-child(2){
  background-image: url("googleplay-button.png");
}


@media (max-width: 1024px) {
  .açougueiro-wrapper{
    width: 90%;
  }
}

@media (max-widht: 650px) {
  body{
    background-color: #000000;
  }
  .açougueiro-wrapper{
    width: 90%;
  }

  .açougueiro-phone{
    display: none;
  }

  .açougueiro-continue{
    width: 100%;
  }

  .group{
    border: 1px solid transparent;
  }
}
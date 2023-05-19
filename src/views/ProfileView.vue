<template>
    <div class="profile">
        <div class="image">
            <img class="avatar"
                src="https://sun9-44.userapi.com/impg/iMZMTCgq2i7Hw6e4zXtxMTrDdWJFIWDz6yAuaw/5O8SMgDbYKA.jpg?size=863x863&quality=96&sign=96256f43a32bfc45e0059371be21275f&type=album" />
        </div>
        <h1>
            Золослав Таблоедов
        </h1>
        <div class="status blocked">
            Заблокирован
        </div>
        <div class="info">
            <div class="profile-card-inf">
                <div class="profile-card-inf__item">
                    <div class="profile-card-inf__title">245</div>
                    <div class="profile-card-inf__txt">Часов записи</div>
                </div>

                <div class="profile-card-inf__item">
                    <div class="profile-card-inf__title">72</div>
                    <div class="profile-card-inf__txt">Бронирований</div>
                </div>

                <div class="profile-card-inf__item">
                    <div class="profile-card-inf__title">32</div>
                    <div class="profile-card-inf__txt">Штрафов</div>
                </div>

                <div class="profile-card-inf__item">
                    <div class="profile-card-inf__title">84</div>
                    <div class="profile-card-inf__txt">Часов бана</div>
                </div>
            </div>
            
        </div>

        <div class="profile-card-send-message">
            Отправить сообщение
        </div>
    </div>
</template>

<style lang="scss">
h1 {
    text-align: center;
}

.image {
    margin-top: 40px;
    text-align: center;

    .avatar {
        border-radius: 50%;
        height: 250px;
        width: 250px;
    }
}

.profile-card-inf {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    align-items: flex-start;
    margin-top: 35px;

    .profile-card-inf__item {
        text-align: center;
        width: 50%;
        min-width: 150px;
        margin-bottom: 20px;
        margin-top: 20px;

        .profile-card-inf__title {
            font-size: 24pt;
        }

        .profile-card-inf__txt {
            font-size: 16pt;
        }
    }
}
.profile-card-send-message {
    margin: 30px 25px;
    padding: 15px;
    background-color: #42b983;
    color: white;
    text-align: center;
    text-transform: uppercase;
    font-size: 16pt;
    border-radius: 10px;
}
.blocked {
    padding: 5px 10px;
    border-radius: 10px;
    background-color: black;
    color: white;
    text-align: center;
    margin: 14px 20%;
    text-transform: uppercase;
    font-size: 16pt;
}
</style>
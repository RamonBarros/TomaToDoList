<template>
    <div class="main">
        <img id="login-icon" alt="Vue logo" src="../assets/Logo.svg">
        <div id="login-card">
            <span id="title">Login</span>
            <div class="input col">
                <span class="input-title">Email</span>
                <input type="text" placeholder="Insira o Email">
            </div>
            <div class="input col">
                <span class="input-title">Senha</span>
                <input type="text" placeholder="Insira a Senha">
            </div>
            <span>Não Tem Uma Conta?Cadastre-se</span>
            <button id='login-button' @click="teste">Entrar</button>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    },
    methods: {
        teste() {
            console.log("lalala");
        }
    }
}
</script>

<style scoped>
#login-card {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #C15B5B;
    width: 50rem;
    height: 25rem;
    color: #ffff;
    border-radius: 15px;
    box-shadow: 1px 1px 47px -3px rgba(0, 0, 0, 0.75);
    -webkit-box-shadow: 1px 1px 47px -3px rgba(0, 0, 0, 0.75);
    -moz-box-shadow: 1px 1px 47px -3px rgba(0, 0, 0, 0.75);
}

#title {
    margin: 1rem 0rem 0rem 0rem;
    font-size: 3rem;
}

#login-icon {
    margin: 5rem 0rem 2rem 0rem;
}

.input {
    margin: 1rem 0rem 1rem 0rem;
    align-items: start;

}

.input input {
    width: 35rem;
    height: 2rem;
    border-radius: 15px;
    border: none;
    font-size: 1.5rem;
    padding: 0.3rem;
}

#login-button {
    margin: 1rem 0rem 1rem 0rem;
    width: 10rem;
    height: 4rem;
    border-radius: 15px;
    background-color: #148C3C;
    color: #ffff;
    font-size: 2rem;
}

.input-title {
    font-size: 2rem;
    margin-bottom: 0.5rem;
}
</style>
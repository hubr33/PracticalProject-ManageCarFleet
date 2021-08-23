<template>
  <main>
    <h3>Akceptacja nowego auta do floty</h3>
    <div class="fleetReport">
      <div class="imgSection">
        <img
          src="https://lodz.premiumarena.pl/assets/samochodydemo/BMW-320-xDrive.jpg"
          alt=""
        />
      </div>
      <div class="fleetInfo">
        <h2>Informacje o aucie</h2>
        <div class="fleetWrapper">
          <div class="fleetOne">
            <p>Marka i model: <span>BMW e90 2.0D</span></p>
            <p>Moc: <span>200 KM</span></p>
            <p>Skrzynia: <span>Manualna</span></p>
            <p>Przyspieszenie: <span>6.5s</span></p>
          </div>
          <div class="fleetTwo">
            <p>Spalanie (trasa/miasto): <span>5/10l</span></p>
            <p>Liczba siedzeń: <span>5</span></p>
            <p>Rok produkcji: <span>2005</span></p>
            <p>Naped: <span>Tył</span></p>
          </div>
          <div class="fleetRentCosts">
            <div class="oneToFive">
              <p>1-5 dni</p>
              <p>500zł / dzień</p>
            </div>
            <div class="sixToThirteen">
              <p>6-13 dni</p>
              <p>400zł / dzień</p>
            </div>
            <div class="fourteenPlus">
              <p>14+ dni</p>
              <p>300zł / dzień</p>
            </div>
            <div class="fleetReposit">
              <p>Kaucja</p>
              <p>5000zł</p>
            </div>
          </div>
          <div class="fleetDescription">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Unde quod
            ipsum quia adipisci perspiciatis iste. Esse non totam eos. Ducimus.
          </div>
        </div>
      </div>
      <div class="fleetInformations">
        <p>Oczekiwanie na akceptacje</p>
      </div>
    </div>
    <div class="finishButtons">
      <button class="addCar">Dodaj auto do floty</button>
      <button class="removeCar">Usuń zgłoszenie</button>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style scoped>
@import "./styles/style.css";
</style>

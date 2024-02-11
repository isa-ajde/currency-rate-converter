 // Include bootstrap's CDN in HTML page
   
   <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
      crossorigin="anonymous"
    />

    <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Döviz Kuru Çevirici</title>
    <link rel="stylesheet" href="/ders/bootstrap/bootstrap.min.css" />
    <link rel="stylesheet" href="/ders/döviz kuru/style.css" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <div class="container border p-3 my-4">
      <form>
        <div class="header-wrapper text-center">
          <div class="row">
            <div class="col-md-12">
              <h4 id="headerTitle  " class="text-black">DÖVİZ KURU ÇEVİRİCİ</h4>
            </div>
          </div>
        </div>
        <hr class="text-success" />

        <div class="body-wrapper text-center">
          <div class="row">
            <div class="col-12 col-sm-3">
              <div class="form-floating">
                <input
                  type="number"
                  id="amount"
                  class="form-control"
                  placeholder="Miktar"
                />
                <label for="amount">Miktar</label>
              </div>
            </div>
            <div class="col-5 col-sm-2 my-3 my-sm-0">
              <select
                id="firstCurrencyOption"
                class="form-control p-3 bg-success text-white"
              >
                <option selected>USD</option>
                <option>EUR</option>
                <option>JPY</option>
                <option>BGN</option>
                <option>CZK</option>
                <option>DKK</option>
                <option>GBP</option>
                <option>HUF</option>
                <option>PLN</option>
                <option>RON</option>
                <option>SEK</option>
                <option>CHF</option>
                <option>ISK</option>
                <option>NOK</option>
                <option>HRK</option>
                <option>RUB</option>
                <option>TRY</option>
                <option>AUD</option>
                <option>BRL</option>
                <option>CAD</option>
                <option>CNY</option>
                <option>HKD</option>
                <option>IDR</option>
                <option>ILS</option>
                <option>INR</option>
                <option>KRW</option>
                <option>MXN</option>
                <option>MYR</option>
                <option>NZD</option>
                <option>PHP</option>
                <option>SGD</option>
                <option>THB</option>
                <option>ZAR</option>
              </select>
            </div>

            <div class="col-2 my-3 my-sm-0" id="icon">
              <i class="bi-arrow-right fs-1 text-white"></i>
            </div>

            <div class="col-5 col-sm-2 my-3 my-sm-0">
              <select
                id="secondCurrencyOption"
                class="form-control p-3 bg-success text-white"
              >
                <option>USD</option>
                <option>EUR</option>
                <option>JPY</option>
                <option>BGN</option>
                <option>CZK</option>
                <option>DKK</option>
                <option>GBP</option>
                <option>HUF</option>
                <option>PLN</option>
                <option>RON</option>
                <option>SEK</option>
                <option>CHF</option>
                <option>ISK</option>
                <option>NOK</option>
                <option>HRK</option>
                <option>RUB</option>
                <option selected>TRY</option>
                <option>AUD</option>
                <option>BRL</option>
                <option>CAD</option>
                <option>CNY</option>
                <option>HKD</option>
                <option>IDR</option>
                <option>ILS</option>
                <option>INR</option>
                <option>KRW</option>
                <option>MXN</option>
                <option>MYR</option>
                <option>NZD</option>
                <option>PHP</option>
                <option>SGD</option>
                <option>THB</option>
                <option>ZAR</option>
              </select>
            </div>
            <div class="col-12 col-sm-3">
              <div class="form-floating">
                <input
                  type="number"
                  id="result"
                  class="form-control"
                  placeholder="Sonuç"
                  readonly
                />
                <label for="amount">Sonuç</label>
              </div>
            </div>
          </div>
        </div>
        <div class="footer-wrapper">
          <div class="row">
            <div class="col-12">
              <button
                type="button"
                class="btn btn-success d-block w-100 my-3"
                id="button"
              >
                Dönüştür
              </button>
            </div>
            <div class="col-12 text-center">
              <div class="caption">
                <span class="text-muted">Captıon-Isa AJDE</span>
              </div>
            </div>
          </div>
        </div>
      </form>
    </div>

    <script src="currency.js"></script>
    <script src="main.js"></script>
  </body>
</html>

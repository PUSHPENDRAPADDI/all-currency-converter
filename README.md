# Introduction

Javascript library to convert currencies

# Installation

```npm install npm i all-currency-converter```

# How to use

```import { convertCurrency } from 'all-currency-converter'```


And Call it as function with parameter

```convertCurrency(fromCurrency,toCurrency, Units)```


# Example


```convertCurrency("USD","INR", 5)```


# Usage

`node`

```js
    const filteredRates = data.find(rate => rate.from === fromCurrency && rate.to === toCurrency);
    return filteredRates.rate * units;
```

# Build

```npm run build```

# Contribute

If you would like to contribute your most welcome. clone the repository.
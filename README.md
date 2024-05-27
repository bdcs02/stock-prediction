# Árfolyamok Elemzése Lineáris Regresszióval

## Bevezetés

Ez a projekt a Bitcoin (BTC-USD) és az Ethereum (ETH-USD) árfolyamainak elemzésére és előrejelzésére koncentrál lineáris regresszió segítségével. A cél a két kriptovaluta közötti kapcsolat feltárása, az árfolyam előrejelzése, valamint egy egyszerű páros kereskedési stratégia tesztelése. Az elemzés magában foglalja a következő lépéseket: adatok letöltése, adatok előkészítése, lineáris regresszió modellezése, eredmények kiértékelése és vizualizálása.

## Követelmények

- Python 3.x
- yfinance
- matplotlib
- numpy
- pandas
- scikit-learn

A szükséges csomagokat a következő parancsokkal telepíthetjük:

```bash
pip install yfinance matplotlib numpy pandas scikit-learn
```

## Következtetések

Az elemzés során kiderült, hogy a BTC és az ETH árfolyamai erős korrelációt mutatnak. Azonban a lineáris regresszió nem tökéletes előrejelzési módszer, mivel az árfolyamok számos tényezőtől függnek. A páros kereskedési stratégia eredményei alapján a modell nem bizonyult nyereségesnek, ami arra utal, hogy további tényezőket is figyelembe kell venni a pontosabb előrejelzés és kereskedési stratégiák kialakításához.

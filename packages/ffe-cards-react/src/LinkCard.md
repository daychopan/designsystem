Lenkekort kommer i flere forskjellige størrelser.

#### Store kort

Hele flaten er klikkbar. Brukes som navigasjon. Brukt som produktkort på nettsidene.

```js
const { KrPoseIkon } = require('@sb1/ffe-icons-react');
<div>
    <LinkCard
        details="kr 32 132,00"
        heading="Innskuddspensjon med investeringsvalg"
        icon={<KrPoseIkon className="sb1ds-icon-color" />}
        size="large"
    />
    <LinkCard
        details="kr 1 354 001,00"
        heading="Pensjonskonto"
        icon={<KrPoseIkon className="sb1ds-icon-color" />}
        size="large"
    />
</div>;
```

#### Mellomstore kort

Hele flaten er klikkbar. Brukes som navigasjon. Brukt som produktkort på nettsidene.

```js
const { KrPoseIkon } = require('@sb1/ffe-icons-react');
<div>
    <LinkCard
        heading="Innskuddspensjon med investeringsvalg"
        icon={<KrPoseIkon className="sb1ds-icon-color" />}
        size="medium"
    />
    <LinkCard
        heading="Pensjonskonto"
        icon={<KrPoseIkon className="sb1ds-icon-color" />}
        size="medium"
    />
</div>;
```

#### Små kort

Hele flaten er klikkbar. Brukes som navigasjon. Dette er også slik produktkortene ser ut på mobil.

```js
const { BilIkon, HusIkon } = require('@sb1/ffe-icons-react');
<div>
    <LinkCard
        details="kr 32 132,00"
        heading="Bilforsikring"
        icon={<BilIkon className="sb1ds-icon-color" />}
    />
    <LinkCard
        details="kr 1 354 001,00"
        heading="Husforsikring"
        icon={<HusIkon className="sb1ds-icon-color" />}
    />
</div>;
```

#### Nummererte kort

```js
<div>
    <LinkCard
        elementType="div"
        heading="Logg inn med BankID, slik at vi vet hvem du er"
        number={1}
        plain={true}
        size="large"
    />
    <LinkCard
        elementType="div"
        heading="Få et godt tilbud på bilforsikring!"
        number={2}
        plain={true}
        size="large"
    />
</div>
```

# d30360e3
* Date difference in years according to the **30E3/360** daycount method
* Synonyms: 30E3/360, Eurobond basis model 3


## ISO 20022 -- A013

    "Method whereby interest is calculated based on a 30-day month and a 360-day year. Accrued interest to a value date on the last day of a month shall be the same as to the 30th calendar day of the same month. This means that a 31st is assumed to be a 30th and the 28 Feb (or 29 Feb for a leap year) is assumed to be equivalent to a 30 Feb. It is a variation of the 30E/360 (or Eurobond basis) method where the last day of February is always assumed to be a 30th, even if it is the last day of the maturity coupon period."

[link](https://www.iso20022.org/15022/uhb/mt565-16-field-22f.htm)


### Installation
```
clib install hcnn/d30360e3
```

Or add to your `package.json` and run `clib install`

```
{ ...
    "dependencies": {
        "hcnn/d30360e3": "0.1.0"
        ...
```

### Test and Demo
Download, compile, and run [test.c](https://github.com/hcnn/d30360e3/blob/master/test.c) and [demo.c](https://github.com/hcnn/d30360e3/blob/master/demo.c)

```
git clone git@github.com:hcnn/d30360e3.git
cd d30360e3
make deps
make validate
make showcase
```

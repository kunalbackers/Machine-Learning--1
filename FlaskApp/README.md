# Machine Learning Deployment Tutorials
Launch machine learning models into production using flask, docker etc.


## Environment and tools
1. scikit-learn
2. pandas
3. numpy
4. flask

## Installation

`pip install scikit-learn pandas numpy flask`

`python model.py`

`python app.py`

![Logo](i1.png)

# 2. Predict House Prices

Download the dataset from [here](https://www.kaggle.com/shivachandel/kc-house-data).

## Environment and tools
1. scikit-learn
2. pandas
3. numpy
4. flask
5. docker

## Installation

`curl -X POST -H "Content-Type: application/json" -d @to_predict_json.json http://localhost:8080/predict_price`

where `to_predict.json` contains:

`{"grade":9.0,"lat":37.45,"long":12.09,"sqft_living":1470.08,"waterfront":0.0,"yr_built":2008.0}`

Output:

```
{
  "predict cost": 1022545.34768284
}
```

## Citing

```
@misc{Kunal:2020,
  Author = {Kunal Bambardekar},
  Title = {Machine-Learning-Deployment-Flask},
  Year = {2019},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/kab1012/Machine-Learning-Deployment-Flask}}
}
```

## Contacts

These are some of my contacts details:

1. [Linkedin](https://in.linkedin.com/in/kunalbambardekar)
2. [GitHub](https://github.com/kab1012)

## License

```
MIT License

Copyright (c) 2020 Kunal Bambardekar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

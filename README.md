# Encode-ordinal-value-from-string-to-num

when you're trying to predict a model but a features value is a string and you need it to be a number:

features = ['carat', 'cut']
target = 'price'
model = LinearRegression()
model.fit(train[features], train[target])

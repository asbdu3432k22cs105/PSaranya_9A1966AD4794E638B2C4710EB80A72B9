def linearSearchProduct(productList,targetProduct):
    indices=[]

    for index,product in enumerate(productList):
        if product==targetProduct:
            indices.append(index)

    return indices



protucts=["shoes","boot","loafer","shoes","sandal","shoes"]
target="shoes"
target2='apple'
result=linearSearchProduct(protucts,target2)
print(result)
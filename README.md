
# Product Recommendation System
This is a product recommendation model that clusters similar products based on a key product and suggests them to the user.

## Necessary Files
To use this model, you will need to download the Amazon clothing dataset, which contains information on approximately 183k products.
<br>
Due to the size of the dataset, it is not available on GitHub. Please download it from the following link:

Dataset Link: https://drive.google.com/drive/folders/1dYorJjRIUPBdxKJTJc_nVk-wa3ZnAp9m?usp=sharing

## Dataset
The Amazon clothing dataset contains 19 features for each product. For this model, considered only 7 features:

1. asin (Amazon standard identification number)
2. brand (brand to which the product belongs to)
3. color (color information of product)
4. product_type_name (type of the product)
5. medium_image_url (URL of the product image)
6. title (title of the product)
7. formatted_price (price of the product)

## Clustering Methods
Used three methods for clustering similar products:

1. Bag of Words (BoW) based product similarity, which clusters products based on similar title names.
2. TF-IDF based product similarity, which clusters products based on similar title names.
3. Visual features based product similarity, which clusters products based on similar images.

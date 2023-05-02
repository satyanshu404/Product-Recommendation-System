# Product-Recommendation-System
This is a Product Recommendation model based on one key product. This model can suggest similar products based on the given one product.

## About Dataset:
Used Amazon chothing dataset in which each product/item has 19 features in the raw dataset and are about 183k in total. <br>
Of these 19 features, considered only 7 features
1. asin (Amazon standard identification number) 
2. brand (brand to which the product belongs to) 
3. color (Color information of product, it can contain many colors as a value) 
4. product_type_name (type of the product) 
5. medium_image_url (url of the image) 
6. title (title of the product) 
7. formatted_price (price of the product)

## Model Used:
Used different methods for clustering the similar products 
1. Bag of Words (BoW) based product similarity on the the basis of similar tittle names
2. TF-IDF based product similarity on the basis of similar tittle names
3. Visual features based product similarity on the basis of similar images 

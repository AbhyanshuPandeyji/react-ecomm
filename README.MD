#### The React Ecommerce Project 
- React
- Strapi - healess cms
- Stripe 
- Hostinger


#### The Start
- client - frontend folder
- api - backend folder

### The Basic Structure 
1 - we have 3 pages 
Home
Categories/Products
Single Product

2 - we are gonna use the RouterProvider for the Rendering in return

3 - we have the same navbar and footer so we are gonna have the layout 
it will include the Outlet component to render our pages 
it will be between the Navbar and the Footer
```
layout = ( 
    <Navbar/>
    <Outlet/>
    <Footer/>
)

```


#### front end ui complete
- sass doesn't work for me so the pure css
- know how to choose classes for the styling and choose it wisely and effectively

#### component created
- navbar - the navigation  
- cart - the items in the modal 
- contact - contact/email letter line
- feature - feature section of the page where we see the special products
- list - to see the products of items in the products page
- footer - the multiple line no links footer 
- slider - the main home page slider with minimal js and state management
- category - the page where we go to specific category of  products based on filters
- card - the container of the products card / section card


#### pages created
- Home - includes - category , feature , contact
- Products - includes the all products with the selection to choose  from the filters present 
- product - a single product page with the images and the right side of same old add to cart section 


##### Now Backend Part #####
- cd api file
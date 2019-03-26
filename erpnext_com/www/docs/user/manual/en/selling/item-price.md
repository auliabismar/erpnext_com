<!-- add-breadcrumbs -->
# Item Price

Item Price is the record in which you can log the selling and buying rate of an item.

### 1. How to create Item Price
1. There are two ways to reach to new Item Price form:

 1. **Selling/Buying/Stock > Items and Pricing > Item Price > New**.
 2. Select the price list and enter the rate.
 3. Save.
 
 Or:
 1. **Item > Click on "+" next to Item Price**.
 2. Select the price list and enter the rate.
 3. Save.
 
Following are the detailed steps to create new Item Price.

##### 1.1 Select Price List

You can create multiple Price List in ERPNext to track Selling and Buying Price List of an item separately. Also if item's selling prices id changing based on territory, or due to other criteria, you can create multiple selling Price List for it.

<img class="screenshot" alt="Item Price list" src="{{docs_base_url}}/assets/img/stock/item-price-1.png">

On selection of Price List, its currency and for selling or buying property will be fetched as well.

To have Item Price fetching in the sales or purchase transaction, you should have Price List id selected in the transaction, just above Item table.

##### 1.2 Select Item

Select item for which Item Price record is to be created. On selection of Item Code, Item Name and Description will be fetched as well.

<img class="screenshot" alt="Item Price list" src="{{docs_base_url}}/assets/img/stock/item-price-2.png">

##### 1.3 Enter Rate

Enter selling/buying rate of an item in Price List currency.

<img class="screenshot" alt="Item Price list" src="{{docs_base_url}}/assets/img/stock/item-price-3.png">

##### 1.4 Save Item Price

To check all Item Price together, go to:

**Stock > Main Report > Itemwise Price List Rate**

You will find option to create new Item Price record (+) in this report as well.

<div>
    <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style>
    <div class='embed-container'>
        <iframe src='https://www.youtube.com/embed/FcOsV-e8ymE?start=193' frameborder='0' allowfullscreen>
        </iframe>
    </div>
</div>

#### 2. Related Topics
1. [Item](/docs/user/manual/en/stock/item)
1. [Applying Discount](/docs/user/manual/en/selling/articles/applying-discount)
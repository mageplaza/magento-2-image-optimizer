# Magento 2 Image Optimizer

[Magento 2 Image Optimizer](https://www.mageplaza.com/magento-2-image-optimizer/) can be considered as a must-have module for Magento 2 stores which have the need to compress and optimize their images. By optimizing the images, you will have the ability to reduce the page loading time, enhance the shopping experience as well as grow the conversion rate considerably. 

## 1. Documentation

- [Installation guide](https://www.mageplaza.com/install-magento-2-extension/)
- [User guide](https://docs.mageplaza.com/image-optimizer/index.html)
- [Introduction page](http://www.mageplaza.com/magento-2-image-optimizer/)
- [Contribute on Github](https://github.com/mageplaza/magento-2-image-optimizer)
- [Get Support](https://github.com/mageplaza/magento-2-image-optimizer/issues)

## 2. FAQ

**Q: I got an error: Mageplaza_Core has been already defined**

A: Read solution [here](https://github.com/mageplaza/module-core/issues/3)

**Q: What image types are supported by Image Optimizer?**

A: Most common image types are supported, including PNG, JPG, and GIF. 

**Q: Can you please let me know about the optimization process?**

A: At first, all files (of the directories that are included) will be scanned. After that, the scanned images will be optimized. 

**Q: Is it possible to set up the optimization process to be automated by a specific schedule?**

A: Yes, it is absolutely possible. With the help of cron, the schedule to scan and optimize the image can be set on a regular basis. 

**Q: How is the quality of the image after optimizing?**

A: Using Magento 2 Image Optimizer, you will have two options, which are Lossless and Custom. Choosing Lossless, you can reduce the size of the image while still retaining the quality of that image. On the contrary, you can define the quality percent of optimized images with the Custom option. However, please keep in mind that small file size equal with worse image quality. 

## 3. How to install Image Optimizer extension for Magento 2

Before installing the extension, please [bought it here](https://www.mageplaza.com/magento-2-image-optimizer/)

Install via composer (recommend). Run the following command in Magento 2 root folder:
(Available only for paid customers)

```
composer require mageplaza/module-image-optimizer
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```


## 4. Highlight Features of Magento 2 Image Optimizer

### Optimize multiple types of images

![Optimize multiple types of images](https://i.imgur.com/xXd6u8v.png)

With [Magento 2 Image Optimizer](https://marketplace.magento.com/mageplaza-module-image-optimizer.html), various types of images such as PNG, JPG, and GIF can be compressed easily by the store admins. These three image types are the most common formats which are used by thousands of online stores to upload the pictures of their products and services. With compressed image size, you will be able to better your store site’s performance. 

### Control image quality: lossless or lossy

![Control image quality](https://i.imgur.com/7u4MUJz.png)

Setting the compression level is the most interesting feature of the Magento 2 Image Optimizer extension. There are two compression options which create different image quality and file size output that you can use: Lossless and Lossy. 

On the one hand, Lossless is an option which allows admin to retain the quantity of image while downsizing its size. More specifically, by removing unnecessary meta data from image files, the file size will be decreased marginally.

On the other hand, Custom compression, also known as Lossy, will help you to reduce the file size dramatically. However, there will be a loss in the data of the original image file; in other words, the quality of the image will be affected. When Magento 2 Image Optimizer extension is applied to your store, the retained proportion of quality after the compression process can be set without a visible loss in image quality. As a result, you can retain full control of image quality as well as the compression level. 

### Process optimization automatically

![Process optimization automatically](https://i.imgur.com/0x8mQiF.png)

You can activate the image compression on a regular basis by running cron. Thanks to this, the admin will no longer need to compress images manually. 

Magento 2 Image Optimizer will scan all the available images and notify you about the optimization status. After that, this module will activate the optimization process to scan than compress images in certain times. Store admins will be able to save a great amount of time with this automated operation. 

### Back up original images

![Back up original images](https://i.imgur.com/ikmN1Rs.png)

To ensure the safety of original images, modifications should accompany with backup. With Magento 2 Image Optimizer, all images will be stored in an image directory, and store admins can roll-back any image and use it at any time if necessary. 

The backup feature allows admins to freely modify the image without worrying about the original picture being lost. 

### Included and excluded images directories

![Included and excluded images directories](https://i.imgur.com/RL7plM0.png)

In addition, you can also assign the image scan to certain directories of your site. From the admin backend, admins can include all directories which have the images being scanned and exclude ones which you would like to keep images from scanning. 

Thanks to this separation, the scanning process will become much more time-saving and focussing. The directories which require original pictures with full quality will not be counted in the optimization process. 

## 5. More Features of Magento 2 Image Optimizer extension

### Force File Permission

Approve/ Disapprove permission for compressed file.

### Skip Transparent Image

Allow skipping the transparent image during the process of optimization

### Record, Requeue And Restore

All scanned paths, original size, optimized size, optimization status, optimized percent, error message are recorded. Also, the status of the optimized image can also be changed to pending and re-optimize. Besides, the optimized images can also be restored to original images. 

### Run Manually

By selecting the Optimize button at the Manage Images grid, you will be able to optimize images manually.

### Bulk Compress

Allow multiple image paths and compress to be selected at the same time. 

### Command Line

Command-line is supported for quick and convenient image optimization.

## 6. Full Image Optimizer Feature List 
### For Store Admins 
#### General 
- Turn on/ off the module
- Turn on/ off image backup feature

#### Optimize Options 
- Choose the quality of compressed images: Lossless or Custom 
- Choose quality proportion of images after the optimization process
- Enable/ Disable skipping transparent images
- Enable/ Disable force file permission

#### Directory 
- Included directory whose images are scanned
- Excluded directories whose images are scanned

#### Cron Job
- Allow/ Disallow scanning images
- Set the schedule for scanning 
- Allow/ Disallow image optimization 
- Set the schedule for optimization 

#### Manage Images
- Allow viewing scanned image paths 
- Allow viewing image status after scanning and optimizing 
- Allow viewing the size of the original and optimized file 
- Allow viewing optimization percent
- Allow viewing error messages during optimizing 
- Allow changing images to pending status 
- Allow restoring images to original status
- Allow viewing progressing percent according to status: Pending, Error, Skipped, Success
- Display popup when compressing multiple images in bulk or click on optimize button 
- Apply command line to optimize images quickly and conveniently 

### For Customers

- Access the information on the page faster 
- Stop wasting too much of time for page loading 
- Experience good shopping time 


## 7. Image Optimizer User Guide 


### How to Configure

#### 1. Configuration

Login to the Admin Magento, choose `Stores > Image Optimizer > Configuration`

![](https://i.imgur.com/KkLkVBW.png)

##### 1.1. General

![](https://i.imgur.com/K0aCEhd.png)

- **Enable**: Select **Yes** to use the module features. Support image types: JPG, PNG, GIF, TIF, BMP.
- **Backup Image**: If **Yes** is selected, the original image will be backed up at `var/ backup_image` directory before being optimized.

##### 1.2. Optimize Options

![](https://i.imgur.com/Fx0TCa1.png)

- **Image Quality**: select the image optimization level, including 2 types:
  - **Custom**: a filter which help to remove some data. Noted that this will reduce the image quality so you should be careful with the level of image quality reduction as the image can be blurry and unclear. 
Choosing **Custom** will show more fields:
    - **Quality Percent**: Enter the percent in the **Quality percent** field which will be limited between 1 and 100. For good image quality, please maintain quality above 90. If left blank, default value is 92.
- **Lossless**: is a data compression filter. This does not reduce image quality but it will require uncompressed images before they can be rendered.
- **Skip Transparent Images**: If **yes** is selected, the white image or transparent image will be skipped during the optimization process. If you want to optimzie these transparent photos, you must **Restore** and **Requeue** them. The second way is just choosing "No" in this field, all the transparent images will be optimized too. 
- **Force File Permission**:
  - If **No** is selected, there is no change on the image permission. 
  - Select **Yes** to provide permission for optimized images. Choose **Yes** will show more fields:
    - **Select Permission**:
      - Enter the number presenting the permission in the **Select Permission** field to choose the permission types for optimized images. You can refer [more information here](http://linuxcommand.org/lc3_lts0090.php). Example: 0755, ...
  - This is a required field. 

##### 1.3. Scan Directory

![](https://i.imgur.com/WTqR0Fh.png)

- **Included Directories**:
  - Click **Add** button to enter the path into the path field. The entered paths will be scanned with images in that path. For example: `pub/media/catalog/product`, `pub/media/customer`. 
  - If left blank, the system will scan the default directory of `pub/media/`. Click **Remove** to delete the entered path.
- **Excluded Directories**:
  - Select **Add** button to enter the path where you don't want to scan the image in that folder. For example: `pub/media/mageplaza`, `pub/ media/logo`.
  - If left blank, there is no limit to scan images with paths. Click **Remove** to delete the path if you still want to optimize the path.
- **Note**: If the path is in both **Excluded Directories** and **Included Directories**, then the scan with that path will not apply.

##### 1.4. Cron job

![](https://i.imgur.com/re50otG.png)

- **Enable Image Scan**: Select **yes** to automatically scan images after a certain period of time and display additional fields:
  - **Scan Schedule**: Enter the time in the **Scan Schedule** field, after the selected time will automatically scan the image. You can refer to [this link](https://www.mageplaza.com/faqs/how-configure-cronjob.html). For example:
    - Enter ***** is every 1 minute automatically scan the image.
    - 20 * / 3 * * * is running every 3 hours on 20 minutes will scan the image.
    - Run Daily: is 00 ***. It will be run at 00:00 daily
    - Run Weekly: 00 ** 7 will be run at 00:00 Sunday, 00 ** 1 will be run at 00:00 Monday
    - Run Month: 001 ** will be run at 00:00 on 01/01/2019.
**Note**: When entering values, between two values linked by spaces, start running scans. For example: * * * * *
- **Enable Optimization**: Select **yes** to automatically optimize with scanned images after a certain time and display additional fields:
  - **Optimization Schedule**: Enter the time in Optimization Schedule field, after the selected time will automatically optimize the scanned images. Unscanned images will not be optimized. The time period entered in Optimization Schedule field is the same as the Scan Schedule field, you can refer to above.
  - **Limit Number of Images**: Enter the number of photos that each time you want to automatically optimize after the selected time period.

#### 2. Manage Images

- Login to the Admin Magento, choose `Stores > Image Optimizer > Manage Images`
- Here recorded and statistics scanned image information and Optimize or not include information of the fields: Path, Status, Original Size, Optimized Size, Compression Level (%), Error Message , ....

![](https://i.imgur.com/MYmY3g3.png)

- Click **Scan Images** button to start scaning all images. Only optimize the scanned images.
- Choose **Optimize Images** button to optimize with the scanned images.
- With **Optimize Action**, you can choose optimize with each image or all scanned images without optimizing, the optimized images will not be optimized anymore.
- If **Restore**, the image returns to skipped status and will ignore the optimize image.
- **Re-Queue**: the image returns to the pending state.
- **Delete**: Delete images that you don't want to optimize.
- **Progress**: recounting the status of the photo with Pending, Error, Skipped, Success.
- Display popup when clicking **Mass Action Optimized** or button **Optimize Image**. When **Optimize** is clicked, the Progress bar displays 0%, and displays the first image. Click **Stop** if you want to stop the pptimize process.

![](https://i.imgur.com/y1ZES6t.png)

- Display the popup when clicking **Stop** with message `Are you sure you want to stop optimizing images?`

![](https://i.imgur.com/13Nw5GP.png)

#### 3. Command line

It is possible to run the following command to optimize images quickly, conveniently and the number of images after each optimize will be based on the value of the Limit Number of Images field in the Configuration section:

```
php bin/magento mpimageoptimizer:optimize
```

Also, please run the following command to scan images following the confiruration at the field **Scan Directory**:

```
php bin/magento mpimageoptimizer:scan
```

**Get more Magento 2 extension on Github**
- [Magento 2 Instagram Feed](https://github.com/mageplaza/magento-2-instagram-feed)
- [Magento 2 Social Login](https://github.com/mageplaza/magento-2-social-login)
- [Magento 2 SEO extension](https://github.com/mageplaza/magento-2-seo)
- [Magento 2 Blog extension](https://github.com/mageplaza/magento-2-blog)
- [Magento 2 Lazy Loading](https://github.com/mageplaza/magento-2-lazy-loading)
- [Magento 2 Security extension](https://github.com/mageplaza/magento-2-security)
- [Magento 2 Cron Schedule](https://github.com/mageplaza/magento-2-cron-schedule)


**Explore our pupular extension:**
- [Magento 2 Order Export](https://www.mageplaza.com/magento-2-order-export/)
- [Magento 2 Custom Stock Status](https://www.mageplaza.com/magento-2-custom-stock-status/)
- [Magento 2 Import / Export Categories](https://www.mageplaza.com/magento-2-import-export-categories/)
- [Magento 2 Import Export CMS](https://www.mageplaza.com/magento-2-import-export-cms/)
- [Magento 2 Mass Product Actions](https://www.mageplaza.com/magento-2-mass-product-actions/)
- [magento 2 Two Factor Authentication extension](https://www.mageplaza.com/magento-2-two-factor-authentication/)

**Our extension on Marketplace:**
- [Magento 2 Popup extension](https://marketplace.magento.com/mageplaza-module-better-popup.html)
- [Magento 2 Multi Flat Rates](https://marketplace.magento.com/mageplaza-module-multi-flat-rates.html)
- [Magento 2 Same Order Number](https://marketplace.magento.com/mageplaza-module-same-order-number.html)
- [Magento 2 Two-Factor Authentication](https://marketplace.magento.com/mageplaza-module-two-factors-authentication.html)
- [Magento 2 Import Export CMS](https://marketplace.magento.com/mageplaza-module-import-export-cms.html)
- [Magento 2 Custom Stock Status](https://marketplace.magento.com/mageplaza-module-custom-stock-status.html)

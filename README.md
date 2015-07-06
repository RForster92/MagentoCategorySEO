# MagentoCategorySEO
Category SEO for Magento. Will need to call in the functions on your chosen category template
Please add the following to your category view.phtml file

$_category->getCatseotitle();   // this will get the SEO Title h1
$_category->getCatseotitleh3(); // this will get the SEO Title h3
$_category->getCatseocolleft(); // this will get the left column of text
$_category->getCatseocolright(); // this will get the right column of text

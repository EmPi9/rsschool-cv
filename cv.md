# My CV
# Who i am?
Hello! My name is Kirill Khrenov i am living in Tatarstan a college student majoring in web-development on 4 course.
***
## Contact information:
My discord: oewrcxakewcrtk.(with a dot). \
My email: empifoc123456789@gmail.com \
Git-hub: [@EmPi9](https://github.com/EmPi9):
***
## What projects do I have?

I have several projects behind me, both Front-end and Back-end in PHP for coursework. Google disk with projects [Front-end](https://drive.google.com/file/d/1pk-urgrJHyjb9qN4P1aHZAZ3R6FHfPG7/view?usp=sharing) and [Front-end with Back-end project](https://drive.google.com/file/d/1sER4dvUvy2tzQWFdYxmi3zfkeCaty0ez/view?usp=sharing). In the future I plan to learn React and TypeScript. Raise my level of English.
***
## I have the following skills:
- HTML
- CSS
- TailwindCSS
- Bootstrap
- Basic JS
- PHP
- PostgreSQL
- Figma
***
## Code example in PHP:
```
<?php require 'layouts/menu.php';?>
<?php include_once './models/store.php';
//$productCount = !empty($_SESSION['cart.qty']) ? $_SESSION['cart.qty'] : 0;
$product = getProduct($_GET['id_product']);
var_dump($product);
?>

<div class="min-w-screen min-h-screen bg-black-300 flex items-center p-5 lg:p-10 overflow-hidden relative">
    <div class="w-full max-w-6xl rounded bg-white shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left">
        <div class="md:flex items-center -mx-10">
            <div class="w-full md:w-1/2 px-10 mb-10 md:mb-0">
            <input name=<?=$product['id_product']?> type="hidden">
                <div class="relative">
                    <img src="./assets/img/<?= $product['img_product'] ?>" class="w-full relative z-10" alt="">
                    <div class="border-4 border-[#F56E1E] absolute top-10 bottom-10 left-10 right-10 z-0"></div>
                </div>
            </div>
            <div class="w-full md:w-1/2 px-10">
                <div class="mb-10">
                    <h1 class="font-bold uppercase text-2xl mb-2"><?= $product['name_product']?></h1>
                    <p class="text-sm uppercase mb-4"><?= $product['type_product']?></p>
                    <p class="text-sm"><?= $product['genre_product']?></p>
                </div>
                <div>
                    <div class="inline-block align-bottom mr-5">
                        <span class="text-3xl leading-none align-baseline">₽</span>
                        <span class="font-bold text-3xl leading-none align-baseline"><?= $product['cost_product'] ?></span>
                    </div> <form id="addProd" class="justify-right">
                    <div class="inline-block align-bottom pt-4">
                        <a id="addToCardElem" href="#" onclick="addProd(<?= $product['id_product']?>)" class="text-[#F56E1E] font-medium transition duration-300 bg-sky-100/0 py-2 px-4
                        border-2 border-[#F56E1E] hover:bg-[#F56E1E] hover:text-white
                        focus:outline-none rounded text-base">В КОРЗИНУ</a>
                        
                    </div><input name="<?= $product['id_product']?>" type="hidden"></form>

                </div>
            </div>
        </div>
        <a href="shop.php">
        <button class=" px-10 py-2 mt-10 bg-black rounded-sm
                  font-medium text-white uppercase
                  ">НАЗАД</button>
        </a>
<?php require 'layouts/footer.php';?>
```
***
### Thank you!

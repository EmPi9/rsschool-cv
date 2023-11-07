<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
    <h1>My CV</h1> 
    <h2>Who am I?</h2>
    <p>Hello! My name is Kirill Khrenov i am a college student majoring in web-development on 4 course. My discord:oewrcxakewcrtk.(with a dot)</p>
    <hr>
    <h2>What projects do I have?</h2>
    <p>I have several projects behind me, both Front-end and Back-end in PHP for coursework. Google disk with projects <a href="https://drive.google.com/file/d/1pk-urgrJHyjb9qN4P1aHZAZ3R6FHfPG7/view?usp=sharing">Front-end project</a> and <a href="https://drive.google.com/file/d/1sER4dvUvy2tzQWFdYxmi3zfkeCaty0ez/view?usp=sharing">Front-end with Back-end project</a>.</p>
    <p>I have the following skills my strengths: HTML, CSS, TailwindCSS, Bootstrap, Basic JS, PHP and PostgreSQL.</p>
    <p>In the future I plan to learn React and TypeScript. Raise my level of English.</p>
    <hr>
    <h3>Exanmple code in PHP: </h3>
    <p>
            &lt;!div class="min-w-screen min-h-screen bg-black-300 flex items-center p-5 lg:p-10 overflow-hidden relative"&gt; <br>
            &lt;div class="w-full max-w-6xl rounded bg-white shadow-xl p-10 lg:p-20 mx-auto text-gray-800 relative md:text-left"&gt; <br>
            &lt;div class="md:flex items-center -mx-10"&gt; <br>
            &lt;div class="w-full md:w-1/2 px-10 mb-10 md:mb-0"&gt; <br>
            &lt;input name=&lt;?=$product['id_product']?&gt; type="hidden"&gt; <br>
            &lt;div class="relative"&gt; <br>
            &lt;img src="./assets/img/&lt;?= $product['img_product'] ?&gt;" class="w-full relative z-10" alt=""&gt; <br>
            &lt;div&gt; class="border-4 border-[#F56E1E] absolute top-10 bottom-10 left-10 right-10 z-0"&gt; <br>
            &lt;/div&gt; <br>
            &lt;/div&gt; <br>
            &lt;/div&gt; <br>
            &lt;div class="w-full md:w-1/2 px-10"&gt; <br>
            &lt;div class="mb-10"&gt; <br>
            &lt;h1 class="font-bold uppercase text-2xl mb-2"><?= $product['name_product']?> <br>
            &lt;p/h1&gt; <br>
            &lt;p class="text-sm uppercase mb-4"&gt;&lt;?= $product['type_product']?&gt;&lt;/p&gt; <br>
            &lt;p class="text-sm"><?= $product['genre_product']?>&gt;/p&gt; <br>
            &lt;/div> <br>
            &lt;div> <br>
            &lt;div class="inline-block align-bottom mr-5"&gt; <br>
            &lt;span&gt; class="text-3xl leading-none align-baseline">₽&gt;/span&gt; <br>
            &lt;span class="font-bold text-3xl leading-none align-baseline"&gt;&lt;?= $product['cost_product'] ?>&lt;/span&gt; <br>
            &lt;/div> <br>
            &lt;form&gt; id="addProd" class="justify-right"&gt; <br>
            &lt;div class="inline-block align-bottom pt-4"&gt; <br>
            &lt;a&gt; id="addToCardElem" href="#" onclick="addProd(&lt;?= $product['id_product']?&gt;)" class="text-[#F56E1E] font-medium transition duration-300 bg-sky-100/0 py-2 px-4 <br>
                                        border-2 border-[#F56E1E] hover:bg-[#F56E1E] hover:text-white <br>
                                        focus:outline-none rounded text-base">В КОРЗИНУ&lt;/a&gt; <br>
                                        &lt;/div&gt; <br>
                                        &lt;/div&gt; <br>
                                        &lt;/div&gt; <br>
                                        &lt;/div&gt; <br>
    </p>
</body>
</html>

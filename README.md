<h1>Type-this|</h1>
<p>A simple Vanilla JavaScript plugin that animates any message you want. No jQuery is needed. No pretentions, just for fun</p>

<h2>Demo</h2>
<p><a href="http://www.mamutlove.es/projects/type-this/" title="Demo" target="_blank">Demo 1</a> | <a href="http://www.mamutlove.es/projects/type-this/index2.html" title="Demo" target="_blank">Demo 2</a> | <a href="http://www.mamutlove.es/projects/type-this/index3.html" title="Demo" target="_blank">Demo 3</a></p>

<h2>Usage</h2>
<p>• Download or fork the repository.</p>
<p>• Include the CSS &amp; Javascript file minify or not in your HTML.</p>
<p>• Ensure you have a container within the DOM any element with the class by default "typethis" or the one you want to use, but remember to set it at the className option.</p>
<p>• Initialize your writer. <pre>var typethis = new Typethis();</pre></p>
<p>• Remember you can customize some features
    <pre>var typethis = new Typethis({
        autoWriting: true,
        autoWritingDelay : 0,
        className : ".typethis",
        delay: 600,
        loop: false,
        speed : [200,600],
        words: ["The sentences", " you want", " to", "be shown"]
    });</pre>
</p>

<h2>Options</h2>
<table>
    <tr>
        <td>autoWriting</td>
        <td>Starts when the page is loaded or it is fired when an events occurs</td>
    </tr>
    <tr>
        <td>autoWritingDelay</td>
        <td>If autoWriting property is false you could set a trigger to fire it or indicate a delay to start writing.</td>
    </tr>    
    <tr>
        <td>className</td>
        <td>The class of the element that the plugin searches within the DOM</td>
    </tr>
    <tr>
        <td>delay</td>
        <td>The time in ms that the sentence is been displayed since it is completed until it is delete</td>
    </tr>
    <tr>
        <td>loop</td>
        <td>Inifinite/Linear</td>
    </tr>
    <tr>
        <td>speed</td>
        <td>Range of time in ms that detemines the speed of the writing</td>
    </tr>
    <tr>
        <td>words</td>
        <td>Your content</td>
    </tr>
</table>

<h2>Final thoughts</h2>
<p>Please, take this <a href="http://www.mamutlove.es/projects/type-this/" title="Demo" target="_blank">Demo</a> as it is, and feel free to download, modify, break, use or destroy this code.</p>

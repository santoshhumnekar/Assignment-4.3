<html>
<head>
<style> 
div:hover {
    width: 100px;
    height: 100px;
    text-align: center;
    -webkit-animation-name: example; /* Safari 4.0 - 8.0 */
    -webkit-animation-duration: 4s; /* Safari 4.0 - 8.0 */
    animation-name: example;
    animation-duration: 4s;
}

/* Safari 4.0 - 8.0 */
@-webkit-keyframes example {
    from {background-color: green;}
    to {background-color: orange;}
}
/* Standard syntax */
@keyframes example {
    from {background-color: green;}
    to {background-color: orange;}
}
</style>
</head>
<body>

<div>BOX</div>

</body>
</html>

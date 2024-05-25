<h2 align="center"> Languages & Tools </h2>
<br/>
<div align="center">
  <a href="http://skillicons.dev">
    <img src=http://skillicons.dev/icons?i=<span class="tooltiptext">unity</span>,vscode,dotnet,cs,c,python,java,kotlin,androidstudio,mysql,figma /><br>
    <img src=http://skillicons.dev/icons?i=html,css,javascript,jquery,nodejs,php /><br>
  </a>    
</div>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
}

.tooltip {
    position: relative;
    display: inline-block;
    cursor: pointer;
}

.tooltip img {
    width: 50px;
    height: 50px;
}

.tooltip .tooltiptext {
    visibility: hidden;
    width: 120px;
    background-color: black;
    color: #fff;
    text-align: center;
    border-radius: 5px;
    padding: 5px;
    position: absolute;
    z-index: 1;
    bottom: 125%; /* Position the tooltip above the icon */
    left: 50%;
    margin-left: -60px;
    opacity: 0;
    transition: opacity 0.3s;
}

.tooltip:hover .tooltiptext {
    visibility: visible;
    opacity: 1;
}

# Curriculum vitae
## **Andrei Kaptsiuh**
  **Phone:** *8(025)6284637*  
  **Telegram:** *@andreikaptsiuh*

I want learn programming and find good job in this sphere. For this i have a time, energy and motivation. 
  Now i study Java Script, HTML and CSS. You can wath my code on JS: 
  
```javascript  
    function calculate(){
    let square = +squareInput.value;

    let typeReconstructionCost;
    typeReconstructionElements.forEach(function(x){
        if(x.checked){
            typeReconstructionCost = +x.value;
        }
    })

    let typeBuildingCost;
    typeBuildingElements.forEach(function(x){
        if(x.checked){
            typeBuildingCost = +x.value;
        } 
    })

    let roomsElementsCost;
    roomsElements.forEach(function(x){
        if(x.checked){
            roomsElementsCost = +x.value;
        }
    })
    
    let ceilingCost = ceilings.checked ? +ceilings.value : 1;
    let wallCost = walls.checked ? +walls.value : 1;
    let floorCost = floor.checked ? +floor.value : 1;
    
    const totalPrice = basePricePerimetr * square * typeReconstructionCost * 
    typeBuildingCost * roomsElementsCost * ceilingCost * wallCost * floorCost;

    const formatter = new Intl.NumberFormat("ru");
    totalPriceElement.innerText = formatter.format(parseInt(totalPrice));    
};
```

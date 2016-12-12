/***********************
* Adobe Edge Animate Composition Actions
*
* Edit this file with caution, being careful to preserve 
* function signatures and comments starting with 'Edge' to maintain the 
* ability to interact with these actions from within Adobe Edge Animate
*
***********************/
(function($, Edge, compId){
var Composition = Edge.Composition, Symbol = Edge.Symbol; // aliases for commonly used Edge classes

   //Edge symbol: 'stage'
   (function(symbolName) {
      
      
      Symbol.bindElementAction(compId, symbolName, "${tombolonoff2}", "click", function(sym, e) {
         if (sym.$("NOL").is(":visible")) {
         	sym.getSymbol("BH_L").play();
         	sym.$("Result_A").hide();
         	sym.$("Result_B").show();
         	sym.$("NOL").hide();
         }
         else {
         	if(sym.$("Result_B").is(":visible")){
         	sym.getSymbol("BH_L").playReverse();
         	sym.$("Result_B").hide();
            sym.$("Result_A").hide();
            sym.$("NOL").show();
            }
            else
            {
         		if(sym.$("Result_A").is(":visible")){
         		sym.getSymbol("BH_L").playReverse();
         		sym.$("Result_B").hide();
         		sym.$("Result_A").hide();
         		sym.$("NOL").hide();
         		}
         	else{
            sym.getSymbol("BH_L").play();
            sym.$("Result_A").show();
         	sym.$("Result_B").hide();
         	sym.$("NOL").hide();
            }
            }
         }

      });
      //Edge binding end

      Symbol.bindTriggerAction(compId, symbolName, "Default Timeline", 0, function(sym, e) {
         sym.stop();

      });
      //Edge binding end

      Symbol.bindElementAction(compId, symbolName, "${tombolonoff2Copy}", "click", function(sym, e) {
         
         if (sym.$("Result_B").is(":visible")){
         		sym.getSymbol("BH_R").playReverse();
         		sym.$("Result_A").show();
         		sym.$("Result_B").hide();
         		sym.$("NOL").hide();
         	}
         else if (sym.$("NOL").is(":visible")){
         		sym.getSymbol("BH_R").playReverse();
         		sym.$("Result_A").hide();
         		sym.$("Result_B").hide();
         		sym.$("NOL").hide();
         	}
         else {
         	if (sym.$("Result_A").is(":visible")) {
         	sym.getSymbol("BH_R").play();
         	sym.$("Result_A").hide();
         	sym.$("Result_B").show();
         	sym.$("NOL").hide();
         	}
         	else {
         		sym.getSymbol("BH_R").play();
         		sym.$("Result_A").hide();
         		sym.$("Result_B").hide();
         		sym.$("NOL").show();
         }
         
         
         }
         

      });
      //Edge binding end

   })("stage");
   //Edge symbol end:'stage'

   //=========================================================
   
   //Edge symbol: 'batang1'
   (function(symbolName) {   
   
   })("batang1");
   //Edge symbol end:'batang1'

   //=========================================================
   
   //Edge symbol: 'L_B'
   (function(symbolName) {   
   
   })("L_B");
   //Edge symbol end:'L_B'

   //=========================================================
   
   //Edge symbol: 'R_L'
   (function(symbolName) {   
   
   })("R_L");
   //Edge symbol end:'R_L'

   //=========================================================
   
   //Edge symbol: 'BH_L'
   (function(symbolName) {   
   
   })("BH_L");
   //Edge symbol end:'BH_L'

   //=========================================================
   
   //Edge symbol: 'BH_R'
   (function(symbolName) {   
   
   })("BH_R");
   //Edge symbol end:'BH_R'

})(window.jQuery || AdobeEdge.$, AdobeEdge, "EDGE-13364392");
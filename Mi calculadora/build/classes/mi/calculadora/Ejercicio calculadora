package mi.calculadora;
import java.lang.Math;
public class MiCalculadora {
    
   private String cadena;
   private double resultado;
   private boolean suma;
   private boolean resta;
   private boolean multiplicacion;
   private boolean division;
   private boolean raiz;
   private boolean seno;
   private boolean coseno;
   private boolean tangente;
   private boolean potenciaeneisma;
   
   public MiCalculadora(){
   
       cadena="";
       suma=false;
       resta=false;
       multiplicacion=false;
       division=false;
       raiz=false;
       seno=false;
       coseno=false;
       tangente=false;
       potenciaeneisma=false;
   
   }
   
   public String concatenamiento(String cadena){
   
       this.cadena=this.cadena+cadena;
       return this.cadena;
       
   
   }
   
   public void suma(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       suma=true;
       this.cadena="";
   
   }
   
    public void resta(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       resta=true;
       this.cadena="";
   
   }
    
     public void multiplicacion(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       multiplicacion=true;
       this.cadena="";
   
   }
     
      public void division(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       division=true;
       this.cadena="";
   
   }
      
       public void raiz(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       raiz=true;
       this.cadena="";
   
   }
       
        public void seno(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       seno=true;
       this.cadena="";
   
   }
        
         public void coseno(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       coseno=true;
       this.cadena="";
   
   }
         
       public void tangente(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       tangente=true;
       this.cadena="";
   
   }
              
        public void potenciaeneisma(String cadena){
   
       this.resultado=Double.parseDouble(cadena);
       potenciaeneisma=true;
       this.cadena="";
   
   }
      
 public double resultado(String numero){
   
       if(suma==true){
           
       resultado=resultado+Double.parseDouble(numero);
       
       }
       
       else if(resta==true){
           
       resultado=resultado-Double.parseDouble(numero);
       
       }
       
           else if(multiplicacion==true){
           
       resultado=resultado*Double.parseDouble(numero);
       
       }
       
           else if(division==true){
           
       resultado=resultado/Double.parseDouble(numero);
       
       }
       
           else if(raiz==true){
           
       resultado=Math.sqrt(Double.parseDouble(numero));
       
       }
       
           else if(seno==true){
           
               double Seno=Math.toRadians(resultado);
               resultado=Math.sin(Seno);
           }
       
        else if(coseno==true){
           
               double Coseno=Math.toRadians(resultado);
               resultado=Math.cos(Coseno);
           }
       
        else if(tangente==true){
           
               double Tangente=Math.toRadians(resultado);
               resultado=Math.tan(Tangente);
           }
      
        else if(potenciaeneisma==true){
        
            resultado=Math.pow(resultado, Double.parseDouble(numero));
        }
       

       
       suma=false;
       resta=false;
       multiplicacion=false;
       division=false;
       raiz=false;
       seno=false;
       coseno=false;
       tangente=false;
       potenciaeneisma=false;
       
       return resultado;
 }
}



    

package com.example.parcial3;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}


public class poli extends Factura{
    @Override
    public void calcular(String producto, int cantidad, int monto, int codigo){
        super.monto=monto;
        this.codigo=codigo;
    }
}



//RECURSIVIDAD

public class recur{
    public int dividir(int x) {
        x = 16;
        if ((x == 0) || (x == 1)) {
            return 0;
        } else if ((x != 0) || (x != 1)) {
        x = x / 2;
    }else{
        System.out.println("No se pudo");
    }
}``
}










package com.example.parcial3;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity2 extends AppCompatActivity {



    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main2);
    }
}

public class Factura{
    String producto;
    int cantidad;
    int monto;
    int codigo;
    public void principal(){
        this.producto=producto;
        this.cantidad=cantidad;
        this.monto=monto;
    }
    public void fac(){
        producto = "Nevera";
        cantidad = 4;
        monto = 6000;
        codigo = 457;
    }
    public static void main(String[]args){
        System.out.println("La factura por"+producto+"con el codigo"+codigo+"llego en "+monto+"Por la cantidad de "cantidad"unidades.");
    }
}















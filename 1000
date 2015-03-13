package com.example.leanna.p005;

import android.support.v7.app.ActionBarActivity;
import android.os.Bundle;
import android.view.Menu;
import android.view.MenuItem;
import android.app.Activity;
import android.view.View;
import android.widget.Button;
import android.widget.CheckBox;
import android.widget.TextView;


//public class MainActivity extends ActionBarActivity {
    public class MainActivity extends Activity implements View.OnClickListener {

    TextView txt2;
    TextView txt1;
    TextView txt3;
    Button btnK;
    Button btnD;
    Button btnV;
    Button btnT;
    Button btn10;
    Button btnClear;
    int ii= 0;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.game);

        // найдем View-элементы
        txt1 = (TextView) findViewById(R.id.txt1);
        txt3 = (TextView) findViewById(R.id.txt3);
        txt2 = (TextView) findViewById(R.id.txt2);
        btnK = (Button) findViewById(R.id.btnK);
        btnD = (Button) findViewById(R.id.btnD);
        btnV = (Button) findViewById(R.id.btnV);
        btnT = (Button) findViewById(R.id.btnT);
        btn10 = (Button) findViewById(R.id.btn10);
        btnClear = (Button) findViewById(R.id.btnClear);

        // присваиваем обработчик кнопкам
        btnK.setOnClickListener(this);
        btnD.setOnClickListener(this);
        btnV.setOnClickListener(this);
        btnT.setOnClickListener(this);
        btn10.setOnClickListener(this);
        btnClear.setOnClickListener(this);
    }


    public void onClick(View v) {
        // по id определеяем кнопку, вызвавшую этот обработчик
        switch (v.getId()) {
            case R.id.btnK:
                // кнопка ОК
                txt1.setText(txt1.getText()+"+4");
                txt2.setText(txt2.getText()+"+K");
                ii = ii + 4;
                txt3.setText(ii+"");
                break;
            case R.id.btnD:
                // кнопка Cancel
                txt1.setText(txt1.getText()+"+3");
                txt2.setText(txt2.getText()+"+Д");
                ii = ii + 3;
                txt3.setText(ii+"");
                break;
            case R.id.btnV:
                // кнопка Cancel
                txt1.setText(txt1.getText()+"+2");
                txt2.setText(txt2.getText()+"+В");
                ii = ii + 2;
                txt3.setText(ii+"");
                break;
            case R.id.btnT:
                // кнопка Cancel
                txt1.setText(txt1.getText()+"+11");
                txt2.setText(txt2.getText()+"+Т_");
                ii = ii + 11;
                txt3.setText(ii+"");
                break;
            case R.id.btn10:
                // кнопка Cancel
                txt1.setText(txt1.getText()+"+10");
                txt2.setText(txt2.getText()+"+10");
                ii = ii + 10;
                txt3.setText(ii+"");
                break;
            case R.id.btnClear:
                // кнопка Clear
                txt1.setText("");
                txt2.setText("");
                ii = 0;
                txt3.setText(ii+"");
                break;
        }
    }

}

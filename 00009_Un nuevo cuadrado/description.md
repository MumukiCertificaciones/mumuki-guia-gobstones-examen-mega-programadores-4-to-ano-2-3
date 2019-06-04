Tenemos un tablero con un cuadrado azul pero queremos que sea verde. Pero como una imagen vale más que mil palabras :satisfied:, queremos esto:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Azul 1 Negro 0 Rojo 0 Verde 0
        cell 0 1 Azul 1 Negro 0 Rojo 0 Verde 0
        cell 1 0 Azul 1 Negro 0 Rojo 0 Verde 0
        cell 1 1 Azul 1 Negro 0 Rojo 0 Verde 0
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Azul 0 Negro 0 Rojo 0 Verde 1
        cell 0 1 Azul 0 Negro 0 Rojo 0 Verde 1
        cell 1 0 Azul 0 Negro 0 Rojo 0 Verde 1
        cell 1 1 Azul 0 Negro 0 Rojo 0 Verde 1
        head 0 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

> Hacé un programa que reemplace la bolitas azules por verdes. No te preocupes por dónde queda el cabezal.
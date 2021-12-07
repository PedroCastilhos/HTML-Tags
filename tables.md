```
<table>

      <caption> X </caption> // Título da tabela

      <colgroup>
          <col>
          <col span="2" style="background-color: red">
          <col span="2" style="background-color: blue">
      </colgroup> //Tamanho dos quadrados

      <thead> // Table head
        <tr> // Table row
            <th rowspan="2"></th> //igual a "ocupe duas linhas"
            <th colspan="2" scope="colgroup">Afonso Pena</th> // Table head
				// colspan igual a "ocupar duas colunas"
            <th colspan="2" scope="colgroup">Antônia Pereira</th>
			// colspan igual a "ocupar duas colunas"
        </tr>

        <tr> // Table row
          <th scope="col">Produzidos</th> // Table head
          <th scope="col">Vendidos</th>
          <th scope="col">Produzidos</th>
          <th scope="col">Vendidos</th>
      </tr>
      </thead>


      <tbody> Table body
        <tr>
            <td scope="row">Vassouras</td> // table description
            <td>50</td>
            <td>30</td>
            <td>20</td>
            <td>20</td>
        </tr>

        <tr>
          <td scope="row">Vassouras</td> // table description
          <td>50</td>
          <td>30</td>
          <td>20</td>
          <td>20</td>
      </tr>
      </tbody>

      <tfoot> // Table foot
        <tr>
          <td>Total:</td>
          <td>2 pessoas</td>
        </tr>
      </tfoot>

</table>
```

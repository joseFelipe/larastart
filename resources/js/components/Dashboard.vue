<template>
  <div class="container">
    <div class="row">
      <div class="card">
        <div class="card-header">
          <h3 class="card-title">Transações do Período</h3>
        </div>
        <!-- /.card-header -->
        <div class="card-body">
          <div id="example1_wrapper" class="dataTables_wrapper dt-bootstrap4">
            <div class="row">
              <div class="col-sm-12 col-md-12">
                <div class="dataTables_length" id="example1_length">
                  <label>
                    Mostrar
                    <select
                      name="example1_length"
                      aria-controls="example1"
                      class="custom-select custom-select-sm form-control form-control-sm"
                    >
                      <option value="10">10</option>
                      <option value="25">25</option>
                      <option value="50">50</option>
                      <option value="100">100</option>
                    </select> linhas
                  </label>
                </div>
              </div>
              <div class="col-sm-12 col-md-6">
                <div id="example1_filter" class="dataTables_filter">
                  <label>
                    Pesquisar:
                    <input
                      type="search"
                      class="form-control form-control-sm"
                      placeholder
                      aria-controls="example1"
                    >
                  </label>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-sm-12">
                <table
                  id="example1"
                  class="table table-bordered table-striped dataTable"
                  role="grid"
                  aria-describedby="example1_info"
                >
                  <thead>
                    <tr role="row">
                      <th
                        class="sorting_asc"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-sort="ascending"
                        aria-label="Rendering engine: activate to sort column descending"
                      >Transação</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="Browser: activate to sort column ascending"
                      >Nome</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="Platform(s): activate to sort column ascending"
                      >Status</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="Engine version: activate to sort column ascending"
                      >Data</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Dt. Repasse</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Parcelas</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Cartão</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Recibo</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Taxa Adm.</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Taxa Transf.</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Valor</th>
                      <th
                        class="sorting"
                        tabindex="0"
                        aria-controls="example1"
                        rowspan="1"
                        colspan="1"
                        aria-label="CSS grade: activate to sort column ascending"
                      >Vl. Líquido</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr role="row" class="odd">
                      <td class="sorting_1">00001</td>
                      <td>Maria dos Santos</td>
                      <td>Disponível</td>
                      <td>05/03/2019</td>
                      <td>05/04/2019</td>
                      <td>1/1</td>
                      <td>**** **** **** 4321 8765</td>
                      <td>...</td>
                      <td>1,00</td>
                      <td>0,20</td>
                      <td>100,00</td>
                      <td>100,00</td>
                    </tr>
                    <tr role="row" class="even">
                      <td class="sorting_1">00002</td>
                      <td>João da Silva</td>
                      <td>Liquidado</td>
                      <td>01/02/2019</td>
                      <td>01/03/2019</td>
                      <td>1/1</td>
                      <td>**** **** **** 1234 5678</td>
                      <td>...</td>
                      <td>0,60</td>
                      <td>0,20</td>
                      <td>60,00</td>
                      <td>60,00</td>
                    </tr>
                    <tr role="row" class="odd">
                      <td class="sorting_1">00003</td>
                      <td>Fernando Duwe</td>
                      <td>Indisponível</td>
                      <td>22/01/2019</td>
                      <td>22/02/2019</td>
                      <td>1/3</td>
                      <td>**** **** **** 1290 3496</td>
                      <td>...</td>
                      <td>1,30</td>
                      <td>0,20</td>
                      <td>130,00</td>
                      <td>130,00</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
            <div class="row">
              <div class="col-sm-12 col-md-5">
                <div
                  class="dataTables_info"
                  id="example1_info"
                  role="status"
                  aria-live="polite"
                >Mostrando 1 à 10 de 57 transações</div>
              </div>
              <div class="col-sm-12 col-md-7">
                <div class="dataTables_paginate paging_simple_numbers" id="example1_paginate">
                  <ul class="pagination">
                    <li class="paginate_button page-item previous disabled" id="example1_previous">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="0"
                        tabindex="0"
                        class="page-link"
                      >Anterior</a>
                    </li>
                    <li class="paginate_button page-item active">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="1"
                        tabindex="0"
                        class="page-link"
                      >1</a>
                    </li>
                    <li class="paginate_button page-item">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="2"
                        tabindex="0"
                        class="page-link"
                      >2</a>
                    </li>
                    <li class="paginate_button page-item">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="3"
                        tabindex="0"
                        class="page-link"
                      >3</a>
                    </li>
                    <li class="paginate_button page-item">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="4"
                        tabindex="0"
                        class="page-link"
                      >4</a>
                    </li>
                    <li class="paginate_button page-item">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="5"
                        tabindex="0"
                        class="page-link"
                      >5</a>
                    </li>
                    <li class="paginate_button page-item">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="6"
                        tabindex="0"
                        class="page-link"
                      >6</a>
                    </li>
                    <li class="paginate_button page-item next" id="example1_next">
                      <a
                        href="#"
                        aria-controls="example1"
                        data-dt-idx="7"
                        tabindex="0"
                        class="page-link"
                      >Próximo</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- /.card-body -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  }
};
</script>

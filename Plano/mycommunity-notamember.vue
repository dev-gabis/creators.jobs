<template>
  <div class="page-mycommunity dash-community ">
    <language-selector />
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-12 mb-5">
          <div class="pd-highlight">
            <h1 class="text-center titulo">
              {{ $t("dash.community.notamember.titulo") }}
            </h1>
            <h4 class="subtitulo text-center">
                {{ $t("dash.community.notamember.subtitulo") }}
            </h4>
          </div>
        </div>

        
      <div class="col-lg-4  card-prices border-terciary mb-3 margin-mobile">
          <div class=" header-secundario title pt-3 mb-10"> <div class="open">Open</div></div>
          <div class="card-body card-secundario text-primary text-center">
            <div class="wrapper-tips mb-5">
              <h5 class="open-txt d-inline-block">
                {{ $t("dash.community.notamember.txt_1") }}
              </h5>
              <span class="seu-plano">
                 {{ $t("dash.community.notamember.txt_1_tip") }}
              </span>
            </div>
             <p class="mb-5 plano">
              {{ $t("dash.community.notamember.txt_5_2_tip") }}
            </p>
            
            <ul class="pb-4">
              <li class="card-text">
                {{ $t("dash.community.notamember.txt_2") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_2_tip')"
                    >?</span
                  >
                </div>
              </li>

             <li class="card-text">
                <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_2_tip')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_novo_1_tip')"
                    >?</span
                  >
                </div>
              </li>

              <li class="card-text">
                {{ $t("dash.community.notamember.txt_novo_2") }}
                <!-- <div class="btn-question d-inline-block m-0">
                  <span class="btn btn-icons terciary m-0" data-toggle="tooltip" data-placement="right" :title='$t("dash.community.notamember.txt_2_tip")'>?</span>
                </div> -->
              </li>

              <li class="card-text">
                {{ $t("dash.community.notamember.txt_3_tip") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_4_tip')"
                    >?</span
                  >
                </div>
              </li>

              <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_5_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_6_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                  <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_7_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                  <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_8_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>
                  <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_9_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>
            </ul>
            <router-link
              to="/dashboard/client/new-briefing"
              class="btn btn-outline-primary sm w-fit-content mt-2"
              >{{ $t("dash.iniciar_b") }}
            </router-link>
          </div>
        </div>
        
        

    

        <div class="col-lg-4 card-prices border-primary mb-3 margin-top-negative margin-mobile pt-3" >
                <div class="btn-maispopular" 
              >Mais popular
              </div>
          
        
          <div class="card-header text-center pt-4"><div class="community">Community</div></div>


          
          <div class="card-body text-primary text-center card-primario">
            <div class="wrapper-tips">
              <h6 class="card-title2 d-inline-block">
                {{ $t("dash.community.notamember.txt_5") }}
              </h6>
            </div>
            <p class="mb-5 plano">
              {{ $t("dash.community.notamember.txt_5_2") }}
            </p>
            <ul>
              <!-- <li class="card-text">{{ $t("dash.community.notamember.txt_6") }}
                <div class="btn-question d-inline-block m-0">
                  <span class="btn btn-icons terciary m-0" data-toggle="tooltip" data-placement="right" :title='$t("dash.community.notamember.txt_6_tip")'>?</span>
                </div>
              </li> -->
              <li class="card-text2">
                {{ $t("dash.community.notamember.txt_7") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_7_tip')"
                    >?</span
                  >
                </div>
              </li>
             
              <!-- <li class="card-text2">
                {{ $t("dash.community.notamember.txt_10") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_9_tip')"
                    >?</span
                  >
                </div>
              </li> -->

              <!-- <li class="card-text2">
                {{ $t("dash.community.notamember.txt_2") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_2_tip')"
                    >?</span
                  >
                </div>
              </li> -->

             <li class="card-text2">
                <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_2_tip')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_novo_1_tip')"
                    >?</span
                  >
                </div>
              </li>

              <li class="card-text2">
                {{ $t("dash.community.notamember.txt_novo_2") }}
                <!-- <div class="btn-question d-inline-block m-0">
                  <span class="btn btn-icons terciary m-0" data-toggle="tooltip" data-placement="right" :title='$t("dash.community.notamember.txt_2_tip")'>?</span>
                </div> -->
              </li>

              <li class="card-text2">
                {{ $t("dash.community.notamember.txt_3_tip") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_4_tip')"
                    >?</span
                  >
                </div>
              </li>

              <li class="card-text2">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_5_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                <li class="card-text2">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_6_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                  <li class="card-text2">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_7_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                  <li class="card-text2">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_8_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>
                  <li class="card-text2">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_9_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>
            </ul>

            <a
              href="mailto:rdg@creators.llc"
              class="btn btn-outline-primary sm w-fit-content"
              >{{ $t("dash.community.notamember.assinar") }}</a>
          </div>
        </div>

        <div
          class="col-lg-4 card-prices border-terciary mb-3 margin-mobile"
        >
          <div class=" header-secundario text-center pt-3"> <div class=" business">Business</div></div>
          <div class="card-body text-primary text-center card-secundario">
            <div class="wrapper-tips mb-2 pb-1">
              <h5 class="business-txt  d-inline-block">
                {{ $t("dash.community.notamember.txt_11") }}
              </h5>
            </div>
             <p class="mb-5 plano">
              {{ $t("dash.community.notamember.txt_5_3_tip") }}
            </p>
            <ul>
              <li class="card-text">
                {{ $t("dash.community.notamember.txt_6") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_6_tip')"
                    >?</span
                  >
                </div>
              </li>
              <li class="card-text">
                {{ $t("dash.community.notamember.txt_12") }}
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_12_tip')"
                    >?</span
                  >
                </div>
              </li>
              <li class="card-text">
                creators wishlist
                <div class="btn-question d-inline-block m-0 card-secundarios">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_8_tip')"
                    >?</span
                  >
                </div>
              </li>
              <li class="card-text">
                {{ $t("dash.community.notamember.txt_13") }}
                <!-- <div class="btn-question d-inline-block m-0">
                  <span class="btn btn-icons terciary m-0" data-toggle="tooltip" data-placement="right" :title='$t("dash.community.notamember.txt_4_tip")'>?</span>
                </div> -->  </li>

                 <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_5_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_6_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                  <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_7_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>

                  <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_8_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>
                  <li class="card-text">
                 <div
                  class="d-inline"
                  v-html="$t('dash.community.notamember.txt_9_plano')"
                ></div>
                <div class="btn-question d-inline-block m-0">
                  <span
                    class="btn btn-icons terciary m-0"
                    data-toggle="tooltip"
                    data-placement="right"
                    :title="$t('dash.community.notamember.txt_5_primeiroPlano')"
                    >?</span
                  >
                </div>
              </li>
            </ul>
            <a
              href="mailto:rdg@creators.llc"
              class="btn btn-outline-primary sm w-fit-content"
              >{{ $t("dash.community.notamember.assinar") }}</a
            >
          </div>
        </div>

        <!-- <div class="col-12 mt-5">
        <p class="black">* Taxas de curadoria, intermediação, processamento e administração de pagamento de 25%</p>
        <p class="black">** Taxas de curadoria, intermediação, processamento e administração de pagamento de 15%</p>
        <p class="black">*** Taxas de curadoria, intermediação, processamento e administração de pagamento regressiva </p>
      </div> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      //
    };
  },
  mounted() {
    $('[data-toggle="tooltip"]').tooltip();
  },
};
</script>

<template>
    <div>
        <section class="protfolio">
            <h1>Portfolio</h1>
            <p>These are suppose to be sample projects</p>
            <div class="container">
                <div class="row">
                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head">
                                    <img alt="Vue logo"
                                      class="rounded-circle img-custome" src="https://cdn.mos.cms.futurecdn.net/wH5y2PkWhCxqKBje8rBp5e.jpg">
                                    <h2>Projektet e perfunduara</h2>
                                </div>
                                <hr>
                                <div class="card-body">
                                    <p>
                                       Ketu kam paraqitur disa prej projekteve te mijat te cilat i kam perfunduara
                                       koheve te fundit. Ka disa prej tyre qe i kemi bere ne menyre ekipore, por ka edhe 
                                       projekte ne te cilat kam punuar vet, per me shume klikoni tekk butoni More.
                                    </p>
                          <button type="button" class="btn btn-outline-secondary">
                            More
                            </button>
                                </div>
                            </div>
                            <br>
                    </div>
                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head">
                                    <img alt="Vue logo" class="rounded-circle img-custome" src="https://i.pinimg.com/originals/4a/70/56/4a70563234301578c158dc142384a1c3.png">
                                    <h2>Hobit e ndryshem</h2>
                                </div>
                                <hr>
                                <div class="card-body">
                                    <p>
                                       Ketu kam paraqitur disa nga hibit e mi me te cilen e kaloj kohen e lire. Ketu kam paraqitur
                                       vetem disa nga honit te cilet i kam kohen e fundit, per me shume klikoni butonin More.
                                    </p>
                                    <button type="button" class="btn btn-outline-secondary">More</button>
                                </div>
                            </div>
                        <br>
                    </div>  
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="Vue logo" class="rounded-circle img-custome" src="https://cdn.mos.cms.futurecdn.net/wH5y2PkWhCxqKBje8rBp5e.jpg">
                                <h2>Synimet per profesion</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    Ne kete pjese kam paraqitur disa nga synimet e mija se cka dua te pervetsoj ne dijen time sa 
                                    i perket anes profesionale. Keto te qe i kam permendur jane synimet e mija per kete vit dhe shpresoj
                                    qe ti arrije, per me shume klikoni butonin More.
                                </p>
                                <button type="button" class="btn btn-outline-secondary">More</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<style scoped>
.protfolio{
        background-color: #34345238;
        padding-top: 8%;
        padding-bottom: 15%;
        /* padding:15% */
    }
    .img-custome{
        width: 140px;
        height: 140px;
        margin-top: 15px;
    }
</style>
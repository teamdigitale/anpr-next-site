---
title: Strumenti di lavoro
subtitle: Strumenti di lavoro, documenti e forum utili a tutti coloro che sono al lavoro per costruire l'anagrafe nazionale.
layout: internal
own_menu : menu_progetto
---

<div class="strumentilavoro">
<div class="container strumentilavoro__container">
    <div class="row row-equal-height">
        <article class="col-md-6 strumentilavoro__cell sx">
            <h5>PER GLI AMMINISTRATORI DELLA PA</h5>
            <h1>Compila il piano di migrazione</h1>
            <p class="mb-4"><img class="float-left mr-3" src="{{'/assets/images/icons/ico-certificate.svg' |relative_url}}"> Sei un responsabile della migrazione <br> del tuo Comune ad ANPR?</p>
            <a href="#" class="btn btn-outline-primary bg-white border-0">Accedi all'area riservata</a>
            <span class="small-2 ml-4">Non hai le credenziali?</span> <a href="#" class="text-white font-weight-bold small-2">Contattaci</a>.
        </article>
        <article class="col-md-6 strumentilavoro__cell dx">
             <h5>PER TUTTI</h5>
            <h1>Newsletter</h1>
            <p class="mb-4">Vuoi rimanere sempre aggiornato sulle novità che riguardano ANPR? Scrivi qui sotto il tuo indirizzo.</p>
            <form class="form-inline strumentilavoro__form">
                <input type="text" class="form-control strumentilavoro__email" id="email" name="email" placeholder="Indirizzo e-mail">
                <button type="submit" class="btn btn-primary  strumentilavoro__submit"> Iscriviti </button>
            </form>
        </article>
    </div>

    {% include strumenti-di-lavoro_community.html %}

    <div class="row strumentilavoro__docsection">
        <div class="col-md-6">
        {% include strumenti-di-lavoro_docs.html %}
        {% include strumenti-di-lavoro_circolari.html %}
        </div>
        <div class="col-md-6">
        {% include strumenti-di-lavoro_norme.html %}
        </div>
    </div>

</div>
</div>
# fa
faq
<section>
    <div class="container pt-5">
      <div class="row">
        <div class="col-md-3">
          <p class="hstyle">FAQ's</p> <img class="question" src="assets/images/question.png"> </div>
        <div class="col-md-9">
          <div class='text-center mb-5'>
            <p class="btag">Usually a list of common questions people have asked about this software</p>
          </div>
          <div class="accordion-wrapper">
            <div class="acc-head card "> What is the Advantage of Online Application </div>
            <div class="acc-body rounded-0"> #1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam amet blanditiis culpa ducimus, fuga labore non repellat veritatis? Dignissimos, officiis! </div>
          </div>
          <div class="accordion-wrapper">
            <div class="acc-head card "> Is this software capable to use-Owner\Manager\Pump boy </div>
            <div class="acc-body rounded-0"> #2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam amet blanditiis culpa ducimus, fuga labore non repellat veritatis? Dignissimos, officiis! </div>
          </div>
          <div class="accordion-wrapper">
            <div class="acc-head card "> Is this software user-friendly </div>
            <div class="acc-body rounded-0"> #3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam amet blanditiis culpa ducimus, fuga labore non repellat veritatis? Dignissimos, officiis! </div>
          </div>
          <div class="accordion-wrapper">
            <div class="acc-head card "> How long it will take to learn this software </div>
            <div class="acc-body rounded-0"> #3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam amet blanditiis culpa ducimus, fuga labore non repellat veritatis? Dignissimos, officiis! </div>
          </div>
          <div class="accordion-wrapper">
            <div class="acc-head card"> Do I need to pay any service charge after buy the software </div>
            <div class="acc-body rounded-0"> #3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam amet blanditiis culpa ducimus, fuga labore non repellat veritatis? Dignissimos, officiis! </div>
          </div>
        </div>
      </div>
    </div>
    <!-- codepen link https://codepen.io/Manmrp/pen/VwKxJjG?editors=1010 -->
  </section>
  /*Accordion of FAQ's section start*/
.accordion-wrapper {
  position: relative;
  margin-bottom: 1.3rem;
}
.acc-head {
  position: relative;
  padding: 1rem 1rem 1rem 3.5rem;
  color: gray;
  border-radius: 14px;
}
.acc-head::after {
  content: "\276F";
  position: absolute;
  right: 57px;
  color: grey;
  transform: rotate(90deg);
  transition: 0.4s;

}
.acc-head.active::after {
  content: "\276F";
  position: absolute;
  right: 57px;
  color: grey;
  transform: rotate(269deg);
  transition: 0.4s;
}
.acc-body {
  padding: 1rem;
  display: none;
  background: #dadee2;
  border-radius: 5px !important;
}
.btag  {
    margin-right: 37%;
    font-family: 'futura-Demi';
}

p.hstyle {
    font-size: 41px;
    font-family: futura-medium;
    margin-left: 129px;
    margin-top: -20px;
}
.faq .accordion-list {
  padding: 0 100px;
}

.faq .accordion-list ul {
  padding: 0;
  list-style: none;
}

.faq .accordion-list li + li {
  margin-top: 15px;
}

.faq .accordion-list li {
  padding: 20px;
  background: #fff;
  border-radius: 4px;
  position: relative;
}

.faq .accordion-list a {
  display: block;
  position: relative;
  font-family: "Poppins", sans-serif;
  font-size: 16px;
  line-height: 24px;
  font-weight: 500;
  padding: 0 30px;
  outline: none;
}

.faq .accordion-list .icon-help {
  font-size: 24px;
  position: absolute;
  right: 0;
  left: 20px;
  color: #b1c0df;
}

.faq .accordion-list .icon-show, .faq .accordion-list .icon-close {
  font-size: 24px;
  position: absolute;
  right: 0;
  top: 0;
}

.faq .accordion-list p {
  margin-bottom: 0;
  padding: 10px 0 0 0;
}

.faq .accordion-list .icon-show {
  display: none;
}

.faq .accordion-list a.collapsed {
  color: #343a40;
}

.faq .accordion-list a.collapsed:hover {
  color: #5777ba;
}

.faq .accordion-list a.collapsed .icon-show {
  display: inline-block;
}

.faq .accordion-list a.collapsed .icon-close {
  display: none;
}

@media (max-width: 1200px) {
  .faq .accordion-list {
    padding: 0;
  }
}

/*Accordion of FAQ's section End*/

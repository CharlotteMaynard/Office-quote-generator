<script>
// import HelloWorld from "./components/HelloWorld.vue";

// {{ quotes[1].quote }}

export default {
  name: "App",
  components: {},
  data() {
    return {
      quotes: [
        {
          name: "Andy",
          quote: "I Went To Cornell. Ever Heard Of It?",
          imgSrc: "src/assets/img/Andy.png",
        },
        {
          name: "Andy",
          quote: "Oh, it is on, like a prawn who yawns at dawn.",
          imgSrc: "src/assets/img/Andy.png",
        },
        {
          name: "Andy",
          quote:
            "I'll be the number-two guy here in Scranton in six weeks. How? Name repetition, personality mirroring, and never breaking off a handshake. I'm always thinking one step ahead. Like a... carpenter... that makes stairs",
          imgSrc: "src/assets/img/Andy.png",
        },

        {
          name: "Angela",
          quote:
            "And Since You're Always Having Relationship Problems, I Thought You'd Be Able To Give Me Some Advice.",
          imgSrc: "src/assets/img/Angela.png",
        },
        {
          name: "Angela",
          quote: "It’s not my fault, I was exposed to Harry Potter.",
          imgSrc: "src/assets/img/Angela.png",
        },
        {
          name: "Angela",
          quote: "Then it would say ‘Lanch Party’.",
          imgSrc: "src/assets/img/Angela.png",
        },

        {
          name: "Creed",
          quote:
            "Nobody steals from Creed Bratton and gets away with it. The last person to do this disappeared. His name? Creed Bratton.",
          imgSrc: "src/assets/img/Creed.png",
        },
        {
          name: "Creed",
          quote: "If my parents see this, I'm toast.",
          imgSrc: "src/assets/img/Creed.png",
        },
        {
          name: "Creed",
          quote:
            "I am not offended by homosexuality, in the 60s, I made love to many women, often outdoors in the mud and rain. It’s possible a man could’ve slipped in there. There’d be no way of knowing.",
          imgSrc: "src/assets/img/Creed.png",
        },

        {
          name: "Dwight",
          quote:
            "Whenever I'm about to do something, I think, 'Would an idiot do that?' And if they would, I do not do that thing.",
          imgSrc: "src/assets/img/Dwight.png",
        },
        {
          name: "Dwight",
          quote:
            "All you need is love? False. The four basic human necessities are air, water, food, and shelter.",
          imgSrc: "src/assets/img/Dwight.png",
        },
        {
          name: "Dwight",
          quote: "Those who can’t farm, farm celery.",
          imgSrc: "src/assets/img/Dwight.png",
        },

        {
          name: "Erin",
          quote: "I boiled some Gatorade.",
          imgSrc: "src/assets/img/Erin.png",
        },
        {
          name: "Erin",
          quote: "Talk to me that way again and I’ll cut your face.",
          imgSrc: "src/assets/img/Erin.png",
        },
        {
          name: "Erin",
          quote:
            "You left me in charge of the pens, Pam. That's what happened. The pens happened.",
          imgSrc: "src/assets/img/Erin.png",
        },

        {
          name: "Holly",
          quote: "Your wife becoming me will I.",
          imgSrc: "src/assets/img/Holly.png",
        },
        {
          name: "Holly",
          quote: "Cool. You drive your own car?",
          imgSrc: "src/assets/img/Holly.png",
        },
        {
          name: "Holly",
          quote:
            "It's kind of a good news, bad news situation. The bad news is we're not doing very well, so we really had to starve ourselves this whole week. But the good news is that all the other branches are doing just as bad as we are. So corporate upped the prize to 5 days. So if we stay fat long enough, we may actually get a whole month off.",
          imgSrc: "src/assets/img/Holly.png",
        },

        {
          name: "Jan",
          quote:
            "People underestimate Michael. There are plenty of things that he is well above average at. Like ice skating. He is a very good ice skater.",
          imgSrc: "src/assets/img/Jan.png",
        },
        {
          name: "Jan",
          quote: "Can you spell it? Try to spell it, Pam.",
          imgSrc: "src/assets/img/Jan.png",
        },
        {
          name: "Jan",
          quote:
            "I am taking a calculated risk. What's the upside? I overcome my nausea, fall deeply in love, babies, normalcy, no more self-loathing. Downside? I date Michael Scott publicly and collapse in on myself like a dying star.",
          imgSrc: "src/assets/img/Jan.png",
        },

        {
          name: "Jim",
          quote: "",
          imgSrc: "src/assets/img/Jim.png",
        },
        {
          name: "Jim",
          quote: "",
          imgSrc: "src/assets/img/Jim.png",
        },
        {
          name: "Jim",
          quote: "",
          imgSrc: "src/assets/img/Jim.png",
        },

        {
          name: "Kelly",
          quote: "",
          imgSrc: "src/assets/img/Kelly.png",
        },
        {
          name: "Kelly",
          quote: "",
          imgSrc: "src/assets/img/Kelly.png",
        },
        {
          name: "Kelly",
          quote: "",
          imgSrc: "src/assets/img/Kelly.png",
        },

        {
          name: "Kevin",
          quote: "",
          imgSrc: "src/assets/img/Kevin.png",
        },
        {
          name: "Kevin",
          quote: "",
          imgSrc: "src/assets/img/Kevin.png",
        },
        {
          name: "Kevin",
          quote: "",
          imgSrc: "src/assets/img/Kevin.png",
        },

        {
          name: "Meredith",
          quote: "",
          imgSrc: "src/assets/img/Meredith.png",
        },
        {
          name: "Michael",
          quote: "",
          imgSrc: "src/assets/img/Michael.png",
        },
        {
          name: "Oscar",
          quote: "",
          imgSrc: "src/assets/img/Oscar.png",
        },
        {
          name: "Pam",
          quote: "",
          imgSrc: "src/assets/img/Pam.png",
        },
        {
          name: "Phyllis",
          quote: "",
          imgSrc: "src/assets/img/Phyllis.png",
        },
        {
          name: "Stanley",
          quote: "",
          imgSrc: "src/assets/img/Stanley.png",
        },
        {
          name: "Toby",
          quote: "",
          imgSrc: "src/assets/img/Toby.png",
        },
      ],

      quoteText: "False!",
      quoteName: "",
      imageSource: "",
    };
  },

  props: ["quote"],

  methods: {
    newQuote() {
      let qLength = this.quotes.length;
      let randomNum = Math.floor(Math.random() * qLength);
      console.log(qLength);
      console.log("The random num is" + randomNum);
      this.quoteText = this.quotes[randomNum].quote;
      this.quoteName = this.quotes[randomNum].name;

      console.log(this.quoteName);

      let source = this.quotes[randomNum].imgSrc;
      console.log(source);
      this.imageSource = source;

      // if (this.quoteName == "Dwight") {
      //   let source = this.quotes[randomNum].imgSrc;
      //   console.log(source);
      //   this.imageSource = source;
      // }
    },
  },
};
</script>

<template>
  <div class="container text-center">
    <div class="row">
      <div class="col-12 text-center">
        <div class="h1">The Office</div>
        <div class="h5">Quote generator</div>
      </div>
    </div>
    <div class="row d-flex justify-content-center" style="top: 50px">
      <div class="row d-flex justify-content-center">
        <img class="col-12 rounded-circle overflow-hidden" :src="imageSource" />
      </div>
      <div
        class="col-8 text-center border rounded-pill bg-light"
        style="width: auto"
      >
        <p class="h5 text-black">"{{ quoteText }}"</p>
      </div>
    </div>
    <div class="row" style="top: 60px">
      <div class="col-12 text-center">
        <button class="btn border btn-primary btn-lg rounded" @click="newQuote">
          Generate new quote
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.rounded-circle {
  border-radius: 50%;
  width: 250px;
  height: 200px;
}
</style>

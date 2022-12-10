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
          imgSrc: "./assets/img/img/Andy.png",
        },
        {
          name: "Andy",
          quote: "Oh, it is on, like a prawn who yawns at dawn.",
          imgSrc: "./assets/img/img/Andy.png",
        },
        {
          name: "Andy",
          quote:
            "I'll be the number-two guy here in Scranton in six weeks. How? Name repetition, personality mirroring, and never breaking off a handshake. I'm always thinking one step ahead. Like a... carpenter... that makes stairs",
          imgSrc: "./assets/img/img/Andy.png",
        },

        {
          name: "Angela",
          quote:
            "And Since You're Always Having Relationship Problems, I Thought You'd Be Able To Give Me Some Advice.",
          imgSrc: "./assets/img/img/Angela.png",
        },
        {
          name: "Angela",
          quote: "It’s not my fault, I was exposed to Harry Potter.",
          imgSrc: "./assets/img/img/Angela.png",
        },
        {
          name: "Angela",
          quote: "Then it would say ‘Lanch Party’.",
          imgSrc: "./assets/img/img/Angela.png",
        },

        {
          name: "Creed",
          quote:
            "Nobody steals from Creed Bratton and gets away with it. The last person to do this disappeared. His name? Creed Bratton.",
          imgSrc: "./assets/img/img/Creed.png",
        },
        {
          name: "Creed",
          quote: "If my parents see this, I'm toast.",
          imgSrc: "./assets/img/img/Creed.png",
        },
        {
          name: "Creed",
          quote:
            "I am not offended by homosexuality, in the 60s, I made love to many women, often outdoors in the mud and rain. It’s possible a man could’ve slipped in there. There’d be no way of knowing.",
          imgSrc: "./assets/img/img/Creed.png",
        },

        {
          name: "Dwight",
          quote:
            "Whenever I'm about to do something, I think, 'Would an idiot do that?' And if they would, I do not do that thing.",
          imgSrc: "./assets/img/img/Dwight.png",
        },
        {
          name: "Dwight",
          quote:
            "All you need is love? False. The four basic human necessities are air, water, food, and shelter.",
          imgSrc: "./assets/img/img/Dwight.png",
        },
        {
          name: "Dwight",
          quote: "Those who can’t farm, farm celery.",
          imgSrc: "./assets/img/img/Dwight.png",
        },

        {
          name: "Erin",
          quote: "I boiled some Gatorade.",
          imgSrc: "./assets/img/img/Erin.png",
        },
        {
          name: "Erin",
          quote: "Talk to me that way again and I’ll cut your face.",
          imgSrc: "./assets/img/img/Erin.png",
        },
        {
          name: "Erin",
          quote:
            "You left me in charge of the pens, Pam. That's what happened. The pens happened.",
          imgSrc: "./assets/img/img/Erin.png",
        },

        {
          name: "Holly",
          quote: "Your wife becoming me will I.",
          imgSrc: "./assets/img/img/Holly.png",
        },
        {
          name: "Holly",
          quote: "Cool. You drive your own car?",
          imgSrc: "./assets/img/img/Holly.png",
        },
        {
          name: "Holly",
          quote:
            "It's kind of a good news, bad news situation. The bad news is we're not doing very well, so we really had to starve ourselves this whole week. But the good news is that all the other branches are doing just as bad as we are. So corporate upped the prize to 5 days. So if we stay fat long enough, we may actually get a whole month off.",
          imgSrc: "./assets/img/img/Holly.png",
        },

        {
          name: "Jan",
          quote:
            "People underestimate Michael. There are plenty of things that he is well above average at. Like ice skating. He is a very good ice skater.",
          imgSrc: "./assets/img/img/Jan.png",
        },
        {
          name: "Jan",
          quote: "Can you spell it? Try to spell it, Pam.",
          imgSrc: "./assets/img/img/Jan.png",
        },
        {
          name: "Jan",
          quote:
            "I am taking a calculated risk. What's the upside? I overcome my nausea, fall deeply in love, babies, normalcy, no more self-loathing. Downside? I date Michael Scott publicly and collapse in on myself like a dying star.",
          imgSrc: "./assets/img/img/Jan.png",
        },

        {
          name: "Jim",
          quote:
            "My roommate wants to meet everybody. Because I’m pretty sure he thinks I’m making Dwight up. He is very real.",
          imgSrc: "./assets/img/img/Jim.png",
        },
        {
          name: "Jim",
          quote:
            "I gotta tell you, this baby is amazing. She gets me out of everything, and I… and I love her. I also love her very much.",
          imgSrc: "./assets/img/img/Jim.png",
        },
        {
          name: "Jim",
          quote: "Fact: Bears eat beets. Bears. Beets. Battlestar Galactica.",
          imgSrc: "./assets/img/img/Jim.png",
        },

        {
          name: "Kelly",
          quote: "Cafe Disco? More like Crap-ay Disco.",
          imgSrc: "./assets/img/img/Kelly.png",
        },
        {
          name: "Kelly",
          quote:
            "If I get to stay and Ryan is laid off, I will kill myself, like Romeo and Juliet...the Claire Danes one.",
          imgSrc: "./assets/img/img/Kelly.png",
        },
        {
          name: "Kelly",
          quote:
            "I can't control what I say to people. I spend the whole day talking.",
          imgSrc: "./assets/img/img/Kelly.png",
        },

        {
          name: "Kevin",
          quote:
            "At least once a year I like to bring in some of my Kevin’s favorite chili.",
          imgSrc: "./assets/img/img/Kevin.png",
        },
        {
          name: "Kevin",
          quote:
            "Put back everything in the vending machine, except the fruit.",
          imgSrc: "./assets/img/img/Kevin.png",
        },
        {
          name: "Kevin",
          quote:
            "I hear Angela’s party will have double-fudge brownies. But it will also have Angela.",
          imgSrc: "./assets/img/img/Kevin.png",
        },

        {
          name: "Meredith",
          quote: "Tell ya one thing, I'm not gonna be a good mom tonight.",
          imgSrc: "./assets/img/img/Meredith.png",
        },
        {
          name: "Meredith",
          quote:
            "Yeah, I have this thing about men cutting or threatening to cut my throat. Don't try to cut my throat!",
          imgSrc: "./assets/img/img/Meredith.png",
        },
        {
          name: "Meredith",
          quote:
            "I've never been cheated on, cheated, or been used to cheat with.",
          imgSrc: "./assets/img/img/Meredith.png",
        },

        {
          name: "Michael",
          quote:
            "Do I need to be liked? Absolutely not. I like to be liked. I enjoy being liked. I have to be liked. But it’s not like this compulsive need like my need to be praised.",
          imgSrc: "./assets/img/img/Michael.png",
        },
        {
          name: "Michael",
          quote: "That has sort of an oak-y afterbirth.",
          imgSrc: "./assets/img/img/Michael.png",
        },
        {
          name: "Michael",
          quote: "I… Declare…. Bankruptcy!",
          imgSrc: "./assets/img/img/Michael.png",
        },

        {
          name: "Oscar",
          quote:
            "Our office has an unusually large number of unusually large people.",
          imgSrc: "./assets/img/img/Oscar.png",
        },
        {
          name: "Oscar",
          quote:
            "I didn't realize how many of Angela's opinions I agreed with...until she tried to have my knee caps shattered for sleeping with her husband.",
          imgSrc: "./assets/img/img/Oscar.png",
        },
        {
          name: "Oscar",
          quote:
            "Angela's engaged to a gay man. As a gay man, I'm horrified. As a friend of Angela's, horrified. As a lover of elegant weddings, I'm a little excited.",
          imgSrc: "./assets/img/img/Oscar.png",
        },

        {
          name: "Pam",
          quote:
            "Oh God no, Dwight isn’t my friend… Oh my God! Dwight’s kind of my friend!",
          imgSrc: "./assets/img/img/Pam.png",
        },
        {
          name: "Pam",
          quote: "I feel God in this Chili’s tonight.",
          imgSrc: "./assets/img/img/Pam.png",
        },
        {
          name: "Pam",
          quote:
            "I’m at a crucial point where I have sunk 4 hours into that copier, and I am not going to let it beat me like that wireless router did.",
          imgSrc: "./assets/img/img/Pam.png",
        },

        {
          name: "Phyllis",
          quote:
            "I like being in the same building as Bob. It keeps me honest.",
          imgSrc: "./assets/img/img/Phyllis.png",
        },
        {
          name: "Phyllis",
          quote:
            "Yeah! I love going to the bars with Bob. I wear a tend to wear something low cut, get men to flirt with me... And Bob beats them up ... What?",
          imgSrc: "./assets/img/img/Phyllis.png",
        },
        {
          name: "Phyllis",
          quote: "I thought he knew about the baby I gave away.",
          imgSrc: "./assets/img/img/Phyllis.png",
        },

        {
          name: "Stanley",
          quote: "Are you out of your dang little pea-sized mind?",
          imgSrc: "./assets/img/img/Stanley.png",
        },
        {
          name: "Stanley",
          quote: "If I don’t have some cake soon, I might die.",
          imgSrc: "./assets/img/img/Stanley.png",
        },
        {
          name: "Stanley",
          quote: "Boy have you lost your mind, cause I'll help you find it.",
          imgSrc: "./assets/img/img/Stanley.png",
        },

        {
          name: "Toby",
          quote:
            "Every Halloween I tell him the same thing; you can't bring weapons into the office, and every year he says the same thing; as soon as I get my weapons back I'm gonna kill you.",
          imgSrc: "./assets/img/img/Toby.png",
        },
        {
          name: "Toby",
          quote: "Let's just say I'll be up to my neck in jury duty.",
          imgSrc: "./assets/img/img/Toby.png",
        },
        {
          name: "Toby",
          quote: "Hey you a$$hole! You eat all that dog food yourself!?!",
          imgSrc: "./assets/img/img/Toby.png",
        },
      ],

      quoteText: "I declare.... Quote generator!!",
      quoteName: "",
      imageSource: "./assets/img/img/Michael.png",
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
    <div class="row d-flex justify-content-center" style="top: 10px">
      <div class="row d-flex justify-content-center">
        <img class="col-12 rounded-circle overflow-hidden" :src="imageSource" />
      </div>
      <div class="col-8 text-center border-2 bg-light" style="width: 50%">
        <p class="h5 text-black">"{{ quoteText }}"</p>
      </div>
    </div>
    <div class="row" style="top: 30px">
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

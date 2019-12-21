# awesome-question-answering-dataset [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A list of awesome question answering dataset

## Type of Dataset

* **[Multiple choice](#multiple-choice)**  

* **[Cloze style](#cloze-style)**  

* **[Span Based](#span-based)**  

* **[User log](#user-log)**  


### Multiple choice
-   [MC Test - Eng](https://github.com/voidful/mctest)  
```   
***************************************************
Story:            mc160.test.0
Author:           138354254
Work Time(s):     3100
Todd is a small boy in the town of Rocksville. Todd thinks his town is the best place in the world, and out of all the places in Rocksville, Todd loves to play in Lake Keet the most. Lake Keet is a small lake with fish, plants, and even little shells. Todd's favorite part was the big rock in the middle of the lake. Todd lives pretty close to the lake, so he gets to go there a lot, but could never to get to the rock in the middle. Todd's dad never lets him swim too far because Todd can't swim very well.
During summer, Todd told his dad that he wanted to get to the rock before break ended. Todd's dad told him he had to try his hardest. If he did, then Todd's dad would watch him swim every day. If Todd wanted to try and get to the rock, his dad would follow him there to make sure he was safe. Todd's dad wrote this down in his notebook so he wouldn't forget.
After a week, Todd made his first try to get to the rock, and his dad followed him like he said he would. Todd didn't make it to the rock before he got tired and had to turn around. He practiced even harder for the next two weeks and wanted to try again. So, a month after summer started, Todd tried to reach the rock again. This time, Todd gave it his all and got all the way to the rock. He was very happy, and his dad was very proud of his son's hard work. To celebrate, Todd's dad carved Todd's name and the date into a tree. This way, they would always remember Todd's hard work.
1: multiple: How long was it before Todd made it to the rock?
 A) One month
 B) One week
 C) Two weeks
 D) Two months
2: multiple: What did Todd have to do so his dad would watch him every day?
 A) Try his hardest
 B) Follow his dad to the rock
 C) Get to the big rock
 D) Not swim too far
3: one: What was Todd's favorite part of Lake Keet?
 A) The plants
 B) The big rock
 C) The fish
 D) The small shells
4: one: How did Todd's dad celebrate Todd's hard work?
 A) He wrote down Todd's name and the date in his notebook
 B) He carved Todd's name into a tree
 C) He practiced even harder
 D) He swam to the rock again
```   
-   [TOEFL-QA - Eng](https://github.com/iamyuanchung/TOEFL-QA)  
```   
SENTENCE hi .
SENTENCE i saw your ad in the campus news paper .
SENTENCE oh .
SENTENCE we don't have any job opening right now .
SENTENCE oh ,  no .
SENTENCE i meant the other ad ,  about the services you provide for students .
SENTENCE you see ,  i have been working at the campus tutoring center as a math tutor .
SENTENCE but things have changed ,  including my schedule .
SENTENCE and now i want to start doing tutoring work independently .
SENTENCE but in order to ,  basically ,  start my own business ,  i need to get the work out .
SENTENCE i was thinking i should get something printed up that i can hand out to people .
SENTENCE ah .
SENTENCE well ,  actually ,  i just printed up some great looking flyers for someone doing the same thing .
SENTENCE flyers .
SENTENCE yeah ,  that's an idea .
SENTENCE i guess then i could post them around the campus .
SENTENCE yeah .
SENTENCE and you can hand them out too .
SENTENCE but ,  oh ,  you know what ?
SENTENCE i did something really neat for someone last week .
SENTENCE she didn't want to go the traditional route ,  you know ,  business cards ,  flyers ,  so we customized pencils for her .
SENTENCE yeah .
SENTENCE you know ,  a little message printed on the pencil .
SENTENCE yeah .
SENTENCE but you should know ,  it's not our cheapest option .
SENTENCE oh ,  and you know those little sticky notes ?
SENTENCE well ,  we did once .
SENTENCE i think those bright pieces of paper would be real attention getters .
SENTENCE you know ,  student use them all the time ,  so they should be good for business .
SENTENCE i don't know why we haven't done more .
SENTENCE so you've got some options .
SENTENCE right .
SENTENCE well ,  what about business cards ?
SENTENCE my friend has these business cards .
SENTENCE she does tutoring too .
SENTENCE and she got them at this place in town ,  but they were kind of expensive .
SENTENCE for business card ?
SENTENCE well ,  i don't know what your friend paid .
SENTENCE but we could do something real simple and it wouldn't be much .
SENTENCE like for a batch of 25  for one of our standard designs ,  2  dollars maybe .
SENTENCE now ,  there are some other choices that'll affect the cost .
SENTENCE you know ,  like different background patters ,  using color ink ,  that sort of thing .
SENTENCE and it also depends on how many words you want to include .
SENTENCE ok .
SENTENCE well ,  i know what i want them to say .
SENTENCE but i am just thinking ,  i kind of like that pencil idea .
SENTENCE yeah .
SENTENCE i thought it was neat .
SENTENCE now ,  of course you can only fit your name and phone number ,  and like ,  in your case ,  math tutoring on it .
SENTENCE right .
SENTENCE well ,  i could custom design the business cards through ,  right ?
SENTENCE that's what my friend did .
SENTENCE she said she designed them at the computer right there at the print shop .
SENTENCE well ,  you can do that here too .
SENTENCE but a custom design would be a bigger investment for your business than one of our standard designs .
SENTENCE well ,  i don't know .
SENTENCE i am interested in business cards ,  so can i look at the standard designs ?
QUESTION why does the student go to speak to the man
OPTION to discuss a job opportunity she had heard about 0
OPTION to learn about options for advertising her business 1
OPTION to see if she can change a previous print order 0
OPTION to discuss a design idea that she has for business cards 0
```   
-   [MultiRC - Eng](http://cogcomp.org/multirc/)
```   
{
 "data": [
  {
   "paragraph": {
    "text": "<b>Sent 1: </b>(CNN) -- Air New Zealand's latest in-flight safety video, released Tuesday, is already another viral hit but is encountering some turbulence over its use of several bikini-clad Sports Illustrated models.<br><b>Sent 2: </b>View the video here Previous versions of the video -- starring anything from Hobbits to Bear Grylls to New Zealand's all conquering All Blacks rugby team -- have revolutionized the on-board safety message airlines deliver to passengers.<br><b>Sent 3: </b>The most recent effort though is being criticized by some as neither ground-breaking nor as creative, after the airline teamed up with Sports Illustrated magazine to produce what it's calling \"The world's most beautiful safety video.\"<br><b>Sent 4: </b>The \"Safety in Paradise\" video, which rolls out on Air New Zealand flights at the end of February, is beautifully shot and certainly cheerful and fun.<br><b>Sent 5: </b>It was filmed in the Cook Islands -- home to several stunning beaches -- and coincides with the 50th anniversary of Sports Illustrated's Swimsuit franchise.<br><b>Sent 6: </b>Earlier videos have been witty, clever and quirky but the paradise video combines a far less subtle use of eye-catching material -- using four of the planet's most beautiful, and scantily clad women, to deliver information to passengers.<br><b>Sent 7: </b>The models include Ariel Meredith, Chrissy Teigen, Hannah Davis and Jessica Gomes.<br><b>Sent 8: </b>Christie Brinkley makes a cameo.<br><b>Sent 9: </b>\"It seems that suddenly they are saying that my sexuality is all that matters about me,\" one critic, Massey University lecturer and feminist commentator Deborah Russell told the Sydney Morning Herald.<br><b>Sent 10: </b>Social media reaction to the video was predictably mixed, though the majority of commenters on Facebook and Twitter appeared to support the video -- and the women in it.<br><b>Sent 11: </b>Many praised Air New Zealand for using beautiful women to promote the Cook Islands and complimented the airline on its marketing prowess, given the mass of media attention now being given to the safety video.<br><b>Sent 12: </b>From the negative corner, while some commented they were appalled Air New Zealand would be so sexist, others said the Sports Illustrated version just isn't all that clever -- a disappointing follow up to the airline's creative safety videos of the past.<br>",
    "questions": [
     {
      "question": "Who were the people that opposed Air New Zealand's decisions?",
      "sentences_used": [
       11,
       8
      ],
      "answers": [
       {
        "text": "Deborah Russel and the media who saw the video as sexist",
        "isAnswer": true,
        "scores": {}
       }
      ]
     }
    ]
   }
  }
 ]
}
```   
-   [RACE - Eng](http://www.cs.cmu.edu/~glai1/data/race/)
```   
{
 "answers": [
  "A",
  "C"
 ],
 "options": [
  [
   "People with heart disease all have internal fat.",
   "People can get rid of internal fat by improving diet.",
   "Men are more likely to have too much internal fat.",
   "Exercise can help to reduce the internal fat."
  ],
  [
   "the exact dangers of internal fat",
   "internal fat is the cause of heart disease and diabetes",
   "being slim doesn't mean you are not fat inside",
   "being slim is not dangerous at all"
  ]
 ],
 "questions": [
  "According to the pass age, which of the following is WRONG?",
  "Doctors have found   _  ."
 ],
 "article": "If it really is what's on the inside that counts, then a lot of thin people might be in trouble.\nSome doctors now think that the internal  fat surrounding important organs like the heart or liver could be as dangerous as the external fat which can be noticed more easily.\n\"Being thin doesn't surely mean you are not fat,\" said Dr Jimmy Bell at Imperial College. Since 1994, Bell and his team have scanned nearly 800 people with MRI machines to create \"fat maps\" showing where people store fat.\nAccording to the result, people who keep their weight through diet rather than exercise are likely to have major deposits of internal fat, even if they are slim.\nEven people with normal Body Mass Index scores can have surprising levels of fat deposits inside. Of the women, as many as 45 percent of those with normal BMI scores (20 to 25) actually had too high levels of internal fat. Among men, the percentage was nearly 60 percent.\nAccording to Bell, people who are fat on the inside are actually on the edge of being fat. They eat too many fatty and sugary foods, but they are not eating enough to be fat. Scientists believe we naturally store fat around the belly first, but at some point, the body may start storing it elsewhere.\nDoctors are unsure about the exact dangers of internal fat, but some think it has something to do with heart disease and diabetes. They want to prove that internal fat damages the body's communication systems.\nThe good news is that internal fat can be easily burned off through exercise or even by improving your diet. \"If you want to be healthy, there is no _ . Exercise has to be an important part of your lifestyle,\" Bell said.",
 "id": "high2693.txt"
}
```   
-   [CommonsenseQA - Eng](https://www.tau-nlp.org/commonsenseqa)  
```   
{
 "answerKey": "A",
 "id": "1afa02df02c908a558b4036e80242fac",
 "question": {
  "question_concept": "revolving door",
  "choices": [
   {
    "label": "A",
    "text": "bank"
   },
   {
    "label": "B",
    "text": "library"
   },
   {
    "label": "C",
    "text": "department store"
   },
   {
    "label": "D",
    "text": "mall"
   },
   {
    "label": "E",
    "text": "new york"
   }
  ],
  "stem": "A revolving door is convenient for two direction travel, but it also serves as a security measure at a what?"
 }
}
```   
-   [CosmosQA - Eng](https://wilburone.github.io/cosmos/)  
```   csv
id,context,question,answer0,answer1,answer2,answer3,label
3BFF0DJK8XA7YNK4QYIGCOG1A95STE##3180JW2OT5AF02OISBX66RFOCTG5J7##A2LTOS0AZ3B28A##Blog_56156##q1_a1##378G7J1SJNCDAAIN46FM2P7T6KZEW2,"Do i need to go for a legal divorce ? I wanted to marry a woman but she is not in the same religion , so i am not concern of the marriage inside church . I will do the marriage registered with the girl who i am going to get married . But legally will there be any complication , like if the other woman comes back one day , will the girl who i am going to get married now will be in trouble or Is there any complication ?",Why is this person asking about divorce ?,If he gets married in the church he wo nt have to get a divorce .,He wants to get married to a different person .,He wants to know if he does nt like this girl can he divorce her ?,None of the above choices .,1
```   
-   [C3 - Simplified-Chi](https://dataset.org/c3/)
```   
[
 [
  [
   "男：听说你们公司要派你去南方工作?",
   "女：是呀，虽说那边环境好，待遇也不错，可我还是觉得在家里最好。"
  ],
  [
   {
    "question": "他们在谈论什么?",
    "choice": [
     "旅行",
     "坏境",
     "工作",
     "家庭"
    ],
    "answer": "工作"
   }
  ],
  "47-275"
 ]
]
```   

### Cloze style
-  [CNN/Daily Mail - Eng](https://github.com/deepmind/rc-data)  
```   
[URL]

[Context]

[Question]

[Answer]

[Entity mapping]
```   
-  [LAMBADA - Eng](https://zenodo.org/record/2630551)  
```   
Context: The battery on Logan’s radio must have been on the way out. So he told himself. There was no other explanation beyond Cygan and the staff at the White House having been overrun. Lizzie opened her eyes with a flutter. They had been on the icy road for an hour without incident.
Target sentence: Jack was happy to do all of the . Target word: driving
...
```   
-  [Children's Book Test (CBT) - Eng](https://research.facebook.com/research/babi/)  
```   
Context:
1 So they had to fall a long way .	
2 So they got their tails fast in their mouths .	
3 So they could n't get them out again .	
4 That 's all .	
5 `` Thank you , " said Alice , `` it 's very interesting .	
6 I never knew so much about a whiting before . "	
7 `` I can tell you more than that , if you like , " said the Gryphon .	
8 `` Do you know why it 's called a whiting ? "	
9 `` I never thought about it , " said Alice .	
10 `` Why ? "	
11 `` IT DOES THE BOOTS AND SHOES . '	
12 the Gryphon replied very solemnly .	
13 Alice was thoroughly puzzled .	
14 `` Does the boots and shoes ! "	
15 she repeated in a wondering tone .	
16 `` Why , what are YOUR shoes done with ? "	
17 said the Gryphon .	
18 `` I mean , what makes them so shiny ? "	
19 Alice looked down at them , and considered a little before she gave her answer .	
20 `` They 're done with blacking , I believe . "	
Query: `` Boots and shoes under the sea , " the XXXXX went on in a deep voice , `` are done with a whiting ".
Candidates: Alice|BOOTS|Gryphon|SHOES|answer|fall|mouths|tone|way|whiting	
Answer: gryphon 
```   
-  [PD&CFT - Simplified-Chi](https://github.com/ymcui/Chinese-RC-Dataset)  
```   
9 ||| 所谓 的 “ 傻钱 ” XXXXX ， 其实 就 是 买 入 并 持有 美国 股票 这样 的 普通 组合 。
10 ||| 这个 策略 要 比 对冲 基金 和 其它 专业 投资者 使用 的 更为 复杂 的 投资 方法 效果 好 得 多 。
11 ||| 所谓 的 “ 傻钱 ” XXXXX ， 其实 就 是 买 入 并 持有 美国 股票 这样 的 普通 组合 。 ||| 策略
sentence_id(space)|||(space)Query(space)|||(space)Answer
```   
-  [CliCR - Eng](https://github.com/clips/clicr)
```   
passage:
[. . . ] A gradual improvement in clinical and laboratory status was achieved within 20 days of antituberculous treatment . The patient was then subjected to a thoracic CT scan that also showed significant radiological improvement . Thereafter , tapering of corticosteroids was initiated with no clinical relapse . The patient was discharged after being treated for a total of 30 days and continued receiving antituberculous therapy with no reported problems for a total of 6 months under the supervision of his hometown physicians . [. . . ] query:
If steroids are used , great caution should be exercised on their gradual tapering to avoid .
answer:
relapse (sem type=problem, cui=C0035020)
```   
-  [RecipeQA - Eng](https://hucvl.github.io/recipeqa/)
```   
{
  "data": [
    {
      "recipe_id": "bacon-pancake-poppers",
      "context_modality": [
        "body",
        "title",
        "videos"
      ],
      "split": "val",
      "context": [
        {
          "body": "\n          -Bacon (of course)\n\n\tThis batch of pancake batter will make approximately sixteen half slices of bacon.\n\tFor the batter...\n\t\t1 egg\n\t\t1 cup flour\n\t\t3/4 cup milk\n\t\t2 tablespoons vegetable or canola oil\n\t\t2 tablespoons sugar\n\t\t1 tablespoon baking powder\n\t\t1/2 teaspoon salt\nDon't worry about having extra batter, it makes a great funnel cake.\n\n\t\tjelly (optional)\n\tMy mom loves bacon and jelly, so when I make them for her I insert jelly.\nYou also need...\n\n\t\ta deep fryer (or just a sauce pan)\n\t\tcanola (or other oil) for deep frying\n\t\tskewers\n\t\ta cookie sheet",
          "id": 1,
          "videos": [],
          "title": "You Will Need..."
        },
        {
          "body": "Main ingredient, BACON!\nBegin by preheating your oven to 375o\nCut eight slices of bacon (or however many your making) in half.\nNext, roll and stick on the skewer. You don't want them touching because they don't cook evenly if they are touching.\nPut them in the oven for 30-45 minutes, turning them over about every 15 minutes. If the pan is over flowing with grease, take it out and pour off the excess grease.\nWhen the bacon is done remove from skewers.",
          "id": 2,
          "videos": [],
          "title": "The Bacon"
        },
        {
          "body": "\n          Beat the egg until it is fluffy.\nAdd other ingredients, and stir until smooth.\n\t\t1 egg\n\t\t1 cup flour\n\t\t 3/4 cup milk\n\t\t 2 tablespoons vegetable or canola oil\n\t\t 2 tablespoons sugar\n\t\t 1 tablespoon baking powder\n\t\t 1/2 teaspoon salt",
          "id": 3,
          "videos": [],
          "title": "The Pancake"
        },
        {
          "body": "This is something generally only add if I'm making these for someone who loves bacon with jelly (like my mom).\nTo add jelly simply remove bacon from skewer and unroll. Then, put a small spoonful of jelly in and roll back up.\nOr, if jelly isn't your thing, you could always experiment to find your own favorite fillings.\n---After thought---\nOn this instructables' comment board, Dartssnake suggested using a pastry bag to fill the bacon so that you don't have to roll and re-roll. This should help the bacon maintain it's round shape.",
          "id": 4,
          "videos": [],
          "title": "Jelly (Optional)"
        },
        {
          "body": "Take the bacon bites, and dip into the pancake batter.\nNext, with oil at about 335o, drop bacon with batter into the oil.\nAllow to cook until golden.\nIf you have extra batter, you can just drizzle it into the oil and allow to cook until golden. Then, remove from the oil, and sprinkle with powdered sugar. You have just created a funnel cake.",
          "id": 5,
          "videos": [],
          "title": "Deep Frying"
        },
        {
          "body": "I enjoy dipping these bacony bites in my favorite maple syrup, but the jelly filled ones I eat plain. These aren't just breakfast food! They taste good any time of day.",
          "id": 6,
          "videos": [],
          "title": "Enjoy!"
        }
      ],
      "choice_list": [
        "bacon-pancake-poppers_1_1.jpg",
        "bacon-pancake-poppers_2_2.jpg",
        "bacon-pancake-poppers_3_0.jpg",
        "home-brew-heater-controller_1_1.jpg"
      ],
      "answer": 3,
      "qid": "3000-4995-0-1-2-3",
      "question_modality": [
        "images"
      ],
      "question": [
        "bacon-pancake-poppers_1_1.jpg",
        "bacon-pancake-poppers_2_2.jpg",
        "bacon-pancake-poppers_3_0.jpg",
        "home-brew-heater-controller_1_1.jpg"
      ],
      "task": "visual_coherence",
      "question_text": "Select the incoherent image in the following sequence of images."
    }
  ]
}
```   

### Span Based
-   [SQuAD - Eng](https://rajpurkar.github.io/SQuAD-explorer/)  
```   
{
  "version": "v2.0",
  "data": [
    {
      "title": "Normans",
      "context": "The Norman dynasty had a major political, cultural and military impact on medieval Europe and even the Near East. The Normans were famed for their martial spirit and eventually for their Christian piety, becoming exponents of the Catholic orthodoxy into which they assimilated. They adopted the Gallo-Romance language of the Frankish land they settled, their dialect becoming known as Norman, Normaund or Norman French, an important literary language. The Duchy of Normandy, which they formed by treaty with the French crown, was a great fief of medieval France, and under Richard I of Normandy was forged into a cohesive and formidable principality in feudal tenure. The Normans are noted both for their culture, such as their unique Romanesque architecture and musical traditions, and for their significant military accomplishments and innovations. Norman adventurers founded the Kingdom of Sicily under Roger II after conquering southern Italy on the Saracens and Byzantines, and an expedition on behalf of their duke, William the Conqueror, led to the Norman conquest of England at the Battle of Hastings in 1066. Norman cultural and military influence spread from these new European centres to the Crusader states of the Near East, where their prince Bohemond I founded the Principality of Antioch in the Levant, to Scotland and Wales in Great Britain, to Ireland, and to the coasts of north Africa and the Canary Islands.",
      "paragraphs": [
        {
          "qas": [
            {
              "question": "In what country is Normandy located?",
              "id": "56ddde6b9a695914005b9628",
              "answers": [
                {
                  "text": "France",
                  "answer_start": 159
                },
                {
                  "text": "France",
                  "answer_start": 159
                },
                {
                  "text": "France",
                  "answer_start": 159
                },
                {
                  "text": "France",
                  "answer_start": 159
                }
              ],
              "is_impossible": false
            }
          ]
        }
      ]
    }
  ]
}
```   
-   [NewsQA - Eng](https://datasets.maluuba.com/NewsQA)  
```   
{
    "data": [
        {
            "storyId": "./contoso/stories/2e1d4",
            "text": "Hyrule (Contoso) -- Tingle, Tingle! Kooloo-Limpah! ...These are the magic words that Tingle created himself. Don't steal them!",
            "type": "train",
            "questions": [
                {
                    "q": "What should you not do with Tingle's magic words?",
                    "consensus": {
                        "s": 115,
                        "e": 125
                    },
                    "isAnswerAbsent": 0.25,
                    "isQuestionBad": 0.25,
                    "answers": [
                        {
                            "sourcerAnswers": [
                                {
                                    "s": 115,
                                    "e": 125
                                }
                            ]
                        },
                        {
                            "sourcerAnswers": [
                                {
                                    "noAnswer": true
                                }
                            ]
                        }
                    ],
                    "validatedAnswers": [
                        {
                            "s": 115,
                            "e": 125,
                            "count": 2
                        },
                        {
                            "noAnswer": true,
                            "count": 1
                        },
                        {
                            "badQuestion": true,
                            "count": 1
                        }
                    ]
                }
            ]
        }
    ],
    "version": "1"
}
```   
-   [CMRC2018 - Simplified-Chi](https://hfl-rc.github.io/cmrc2018/task/)  
```   
[
    {
        "title": "傻钱策略"
        "context_id": "TRIAL_0"
        "context_text": "工商协进会报告，12月消费者信心上升到78.1，明显高于11月的72。另据《华尔街日报》报道，2013年是1995年以来美国股市表现最好的一年。这一年里，投资美国股市的明智做法是追着“傻钱”跑。所谓的“傻钱”策略，其实就是买入并持有美国股票这样的普通组合。这个策略要比对冲基金和其它专业投资者使用的更为复杂的投资方法效果好得多。"
        "qas":[
                {
                "query_id": "TRIAL_0_QUERY_0",
                "query_text": "什么是傻钱策略？",
                "answers": [
                     "所谓的“傻钱”策略，其实就是买入并持有美国股票这样的普通组合",
                     "其实就是买入并持有美国股票这样的普通组合",
                     "买入并持有美国股票这样的普通组合"
                    ]
                },
                {
                "query_id": "TRIAL_0_QUERY_1",
                "query_text": "12月的消费者信心指数是多少？",
                "answers": [
                    "78.1",
                    "78.1",
                    "78.1"
                    ]
                },
                {
                "query_id": "TRIAL_0_QUERY_2",
                "query_text": "消费者信心指数由什么机构发布？",
                "answers": [
                    "工商协进会",
                    "工商协进会",
                    "工商协进会"
                    ]
                }
            ]
    }
]
```   
-   [DRCD - Traditional-Chi](https://github.com/DRCSolutionService/DRCD)  
```   
{
"version": "1.3",
"data": [
  {
    "title": "基督新教",
    "id": "2128",
    "paragraphs": [
      {
        "context": "基督新教與天主教均繼承普世教會歷史上許多傳統教義，如三位一體、聖經作為上帝的啟示、原罪、認罪、最後審判等等，但有別於天主教和東正教，新教在行政上沒有單一組織架構或領導，而且在教義上強調因信稱義、信徒皆祭司， 以聖經作為最高權威，亦因此否定以教宗為首的聖統制、拒絕天主教教條中關於聖傳與聖經具同等地位的教導。新教各宗派間教義不盡相同，但一致認同五個唯獨：唯獨恩典：人的靈魂得拯救唯獨是神的恩典，是上帝送給人的禮物。唯獨信心：人唯獨藉信心接受神的赦罪、拯救。唯獨基督：作為人類的代罪羔羊，耶穌基督是人與上帝之間唯一的調解者。唯獨聖經：唯有聖經是信仰的終極權威。唯獨上帝的榮耀：唯獨上帝配得讚美、榮耀",
        "id": "2128-2",
        "qas": [
          {
            "id": "2128-2-1",
            "question": "新教在教義上強調信徒皆祭司以及什麼樣的理念?",
            "answers": [
              {
                "id": "1",
                "text": "因信稱義",
                "answer_start": 92
              }
            ]
          },
          {
            "id": "2128-2-2",
            "question": "哪本經典為新教的最高權威?",
            "answers": [
              {
                "id": "1",
                "text": "聖經",
                "answer_start": 105
              }
            ]
          },
          {
            "id": "2128-2-3",
            "question": "新教認同幾個唯獨?",
            "answers": [
              {
                "id": "1",
                "text": "五個",
                "answer_start": 171
              }
            ]
          },
          {
            "id": "2128-2-4",
            "question": "文中提及，人唯獨藉信心接受神的赦罪、拯救，此為哪一種唯獨?",
            "answers": [
              {
                "id": "1",
                "text": "唯獨信心",
                "answer_start": 206
              }
            ]
          }
        ]
      },
      {
        "context": "主教制源自天主教的主教制度，幾乎和天主教的主教制度一模一樣，唯一不同的是主教亦可以結婚。天主教的主教制是在使徒們去世後於第二、三世紀興起的主教制度，所以可以說主教制是整個基督宗教中歷史最悠久的神職人員制度。現在行主教制的新教教會已經很少，聖公會就是沿用主教制，從教會制度和禮儀上看來，聖公會基本上屬大公教會傳統。路德宗和衛理公會則由各區會自行選擇使用主教制還是長老制；在香港和澳門，路德會和衛理公會就選用了長老制。然而，在歐洲，例如瑞典、芬蘭、挪威、德國等地，他們則通常採用主教制。長老制，是一個以議會形式管理區會的制度。議會內的成員由各教會選出長老，代表該教會出席會議。顧名思義，長老會就是採用長老制的教會。採用長老制的教會有基督教改革宗長老會、台灣基督長老教會、韓國基督長老教會等。",
        "id": "2128-3",
        "qas": [
          {
            "id": "2128-3-1",
            "question": "新教的主教制度源自於哪一教?",
            "answers": [
              {
                "id": "1",
                "text": "天主教",
                "answer_start": 5
              }
            ]
          },
          {
            "id": "2128-3-2",
            "question": "文中提及，新教的主教可以做什麼?",
            "answers": [
              {
                "id": "1",
                "text": "結婚",
                "answer_start": 41
              }
            ]
          },
          {
            "id": "2128-3-3",
            "question": "哪個會屬於大公教會傳統?",
            "answers": [
              {
                "id": "1",
                "text": "聖公會",
                "answer_start": 142
              }
            ]
          },
          {
            "id": "2128-3-4",
            "question": "以議會形式管理區會的制度，名為?",
            "answers": [
              {
                "id": "1",
                "text": "長老制",
                "answer_start": 241
              }
            ]
          }
        ]
      }
    ]
  }
]
}
```   
-   [NarrativeQA - Eng](https://github.com/deepmind/narrativeqa)  
```   csv
document_id,set,question,answer1,answer2,question_tokenized,answer1_tokenized,answer2_tokenized
0025577043f5090cd603c6aea60f26e236195594,test,Who is Mark Hunter?,He is a high school student in Phoenix.,A loner and outsider student with a radio station.,Who is Mark Hunter ?,He is a high school student in Phoenix .,A loner and outsider student with a radio station .
0025577043f5090cd603c6aea60f26e236195594,test,Where does this radio station take place?,It takes place in Mark's parents basement. ,"Phoenix, Arizona",Where does this radio station take place ?,It takes place in Mark s parents basement .,"Phoenix , Arizona"
```   
-   [QAngaroo - Eng](http://qangaroo.cs.ucl.ac.uk/leaderboard.html)
```   
[
 {
  "candidates": [
   "austria",
   "duchy of brunswick",
   "france",
   "german confederation",
   "german empire",
   "germany",
   "holy roman empire",
   "italy",
   "japan",
   "kingdom of france",
   "kingdom of saxony",
   "northern italy",
   "roman empire",
   "russia",
   "saxony",
   "united kingdom",
   "weimar republic",
   "world"
  ],
  "annotations": [
   [
    "follows",
    "single"
   ],
   [
    "follows",
    "multiple"
   ],
   [
    "follows",
    "multiple"
   ]
  ],
  "query": "country sms braunschweig",
  "supports": [
   "The North German Confederation was a confederation of 22 previously independent states of northern Germany, with nearly 30 million inhabitants. It was the first modern German nation state and the basis for the later German Empire (18711918), when several south German states such as Bavaria joined.",
   "Weimar Republic is an unofficial, historical designation for the German state between 1919 and 1933. The name derives from the city of Weimar, where its constitutional assembly first took place. The official name of the state was still \"Deutsches Reich\"; it had remained unchanged since 1871. In English the country was usually known simply as Germany.\nA national assembly was convened in Weimar, where a new constitution for the \"Deutsches Reich\" was written, and adopted on 11 August 1919. In its fourteen years, the Weimar Republic faced numerous problems, including hyperinflation, political extremism (with paramilitaries  both left- and right-wing); and contentious relationships with the victors of the First World War. The people of Germany blamed the Weimar Republic rather than their wartime leaders for the country's defeat and for the humiliating terms of the Treaty of Versailles. However, the Weimar Republic government successfully reformed the currency, unified tax policies, and organized the railway system. Weimar Germany eliminated most of the requirements of the Treaty of Versailles; it never completely met its disarmament requirements, and eventually paid only a small portion of the war reparations (by twice restructuring its debt through the Dawes Plan and the Young Plan). Under the Locarno Treaties, Germany accepted the western borders of the republic, but continued to dispute the Eastern border.",
   "The dreadnought was the predominant type of battleship in the early 20th century. The first of its kind, the Royal Navy's , made such a strong impression on people's minds when launched in 1906 that similar battleships built subsequently were referred to generically as \"dreadnoughts\", and earlier battleships became known as \"pre-dreadnoughts\". \"Dreadnought\"s design had two revolutionary features: an \"all-big-gun\" armament scheme, with more heavy-calibre guns than previous ships, and steam turbine propulsion. As dreadnoughts became a symbol of national power, the arrival of these new warships was a crucial catalyst in the intensifying naval arms race between the United Kingdom and Germany. With the launch of a single ship, \"Dreadnought\", the scales of naval power were reset overnight. As a result, dreadnought races sprang up around the world, including in South America, during the lead up to World War I. Successive designs increased rapidly in size and made use of improvements in armament, armour, and propulsion throughout the dreadnought era. Within five years, new battleships had outclassed \"Dreadnought\". These more powerful vessels were known as \"super-dreadnoughts.\" Most of the original dreadnoughts were scrapped after the end of World War I under the terms of the Washington Naval Treaty, but many of the newer super-dreadnoughts continued to be used throughout World War II. The only surviving dreadnought is , located near the San Jacinto Battleground State Historic Site.",
   "SMS Braunschweig was the first of five pre-dreadnought battleships of the Braunschweig class in the German Kaiserliche Marine ( Imperial Navy ) . She was laid down in 1901 and commissioned in October 1904 , at a cost of 23,983,000 marks . She was named after the then Duchy of Brunswick ( German : Braunschweig ) . Her sister ships were Elsass , Hessen , Preussen , and Lothringen . The ship served in the II Squadron of the German fleet after commissioning , though by the outbreak of World War I she had been moved to the IV Squadron . Braunschweig saw action in the Baltic Sea against the Russian Navy . In August 1915 , the ship participated in the Battle of the Gulf of Riga , during which she engaged the Russian battleship Slava . In 1916 , the ship was placed in reserve owing to crew shortages . She spent the remainder of World War I as a training ship , and after 1917 , as a barracks ship for U-boat crews . Under the terms of the Treaty of Versailles , she was retained after the end of the war and modernized in 1921 -- 22 . Braunschweig served in the reformed Reichsmarine as a coastal defense ship until 1926 , when she was again placed in reserve . She was stricken in 1931 and subsequently broken up for scrap .",
   "World War I (WWI or WW1), also known as the First World War, or the Great War, was a global war originating in Europe that lasted from 28 July 1914 to 11 November 1918. More than 70 million military personnel, including 60 million Europeans, were mobilised in one of the largest wars in history. Over nine million combatants and seven million civilians died as a result of the war (including the victims of a number of genocides), a casualty rate exacerbated by the belligerents' technological and industrial sophistication, and the tactical stalemate caused by gruelling trench warfare. It was one of the deadliest conflicts in history, and paved the way for major political changes, including revolutions in many of the nations involved.",
   "The Free State of Brunswick was a state of the German Reich in the time of the Weimar Republic. It was formed after the abolition of the Duchy of Brunswick in the course of the German Revolution of 191819. Its capital was Braunschweig (Brunswick).",
   "The Congress of Vienna (German: \"Wiener Kongress\") was a conference of ambassadors of European states chaired by Austrian statesman Klemens von Metternich, and held in Vienna from November 1814 to June 1815, though the delegates had arrived and were already negotiating by late September 1814. The objective of the Congress was to provide a long-term peace plan for Europe by settling critical issues arising from the French Revolutionary Wars and the Napoleonic Wars. The goal was not simply to restore old boundaries but to resize the main powers so they could balance each other off and remain at peace. The leaders were conservatives with little use for republicanism or revolution, both of which threatened to upset the status quo in Europe. France lost all its recent conquests, while Prussia, Austria and Russia made major territorial gains. Prussia added smaller German states in the west, Swedish Pomerania and 60% of the Kingdom of Saxony; Austria gained Venice and much of northern Italy. Russia gained parts of Poland. The new Kingdom of the Netherlands had been created just months before, and included formerly Austrian territory that in 1830 became Belgium.\nThe immediate background was Napoleonic France's defeat and surrender in May 1814, which brought an end to twenty-five years of nearly continuous war. Negotiations continued despite the outbreak of fighting triggered by Napoleon's dramatic return from exile and resumption of power in France during the Hundred Days of MarchJuly 1815. The Congress's \"Final Act\" was signed nine days before his final defeat at Waterloo on 18 June 1815.",
   "The German Confederation was an association of 39 German states in Central Europe, created by the Congress of Vienna in 1815 to coordinate the economies of separate German-speaking countries and to replace the former Holy Roman Empire. Most historians have judged the Confederation to have been weak and ineffective, as well as an obstacle to the creation of a German nation-state. It collapsed due to the rivalry between Prussia and Austria, warfare, the 1848 revolution, and the inability of the multiple members to compromise.",
   "The Royal Navy (RN) is the United Kingdom's naval warfare force. Although warships were used by the English kings from the early medieval period, the first major maritime engagements were fought in the Hundred Years War against the kingdom of France. The modern Royal Navy traces its origins to the early 16th century; the oldest of the UK's armed services, it is known as the Senior Service.",
   "Wolfenbüttel is a town in Lower Saxony, Germany, the administrative capital of Wolfenbüttel District. It is best known as the location of the internationally renowned Herzog August Library and for having the largest concentration of timber-framed buildings in Germany. It is an episcopal see of the Evangelical Lutheran Church in Brunswick. It is also home to the Jägermeister distillery and houses a campus of the Ostfalia University of Applied Sciences.",
   "The German Empire (officially ') was the historical German nation state that existed from the unification of Germany in 1871 to the abdication of Kaiser Wilhelm II in November 1918, when Germany became a federal republic (the Weimar Republic).",
   "Braunschweig (Low German: \"Brunswiek\" ), also called Brunswick in English, is a city of 252,768 people (as of 31 December 2015), in the state of Lower Saxony, Germany. It is located north of the Harz mountains at the furthest navigable point of the Oker river, which connects to the North Sea via the rivers Aller and Weser. A powerful and influential centre of commerce in medieval Germany, Braunschweig was a member of the Hanseatic League from the 13th until the 17th century, and the capital of the state of Brunswick until its disestablishment in 1946. Today, Braunschweig is the second largest city in Lower Saxony and a major centre of scientific research and development.",
   "The Washington Naval Treaty, also known as the Five-Power Treaty, and including the \"Four-Power Treaty\" and the \"Nine-power Treaty\" was a treaty among the major nations that had won World War I, which agreed to prevent an arms race by limiting naval construction. It was negotiated at the Washington Naval Conference, held in Washington, D.C., from November 1921 to February 1922, and it was signed by the governments of the United Kingdom, the United States, Japan, France, and Italy. It limited the construction of battleships, battlecruisers and aircraft carriers by the signatories. The numbers of other categories of warships, including cruisers, destroyers and submarines, were not limited by the treaty, but those ships were limited to 10,000 tons displacement.",
   "The Duchy of Brunswick was a historical German state. Its capital was the city of Brunswick (\"Braunschweig\").\nIt was established as the successor state of the Principality of Brunswick-Wolfenbüttel by the Congress of Vienna in 1815. In the course of the 19th-century history of Germany, the duchy was part of the German Confederation, the North German Confederation and from 1871 the German Empire. It was disestablished after the end of World War I, its territory incorporated into the Weimar Republic as the Free State of Brunswick.",
   "World War II (often abbreviated to WWII or WW2), also known as the Second World War, was a global war that lasted from 1939 to 1945, although related conflicts began earlier. It involved the vast majority of the world's nationsincluding all of the great powerseventually forming two opposing military alliances: the Allies and the Axis. It was the most widespread war in history, and directly involved more than 100 million people from over 30 countries. In a state of \"total war\", the major participants threw their entire economic, industrial, and scientific capabilities behind the war effort, erasing the distinction between civilian and military resources. Marked by mass deaths of civilians, including the Holocaust (in which approximately 11 million people were killed) and the strategic bombing of industrial and population centres (in which approximately one million were killed, and which included the atomic bombings of Hiroshima and Nagasaki), it resulted in an estimated 50 million to 85 million fatalities. These made World War II the deadliest conflict in human history."
  ],
  "id": "WH_dev_0",
  "answer": "german empire"
 }
]
```   
-   [QuAC - Eng](http://quac.ai/)
```   
{
  "data": [
    {
      "paragraphs": [
        {
          "context": "In May 1983, she married Nikos Karvelas, a composer, with whom she collaborated in 1975 and in November she gave birth to her daughter Sofia. After their marriage, she started a close collaboration with Karvelas. Since 1975, all her releases have become gold or platinum and have included songs by Karvelas. In 1986, she participated at the Cypriot National Final for Eurovision Song Contest with the song Thelo Na Gino Star (\"I Want To Be A Star\"), taking second place. This song is still unreleased up to date. In 1984, Vissi left her record company EMI Greece and signed with CBS Records Greece, which later became Sony Music Greece, a collaboration that lasted until 2013. In March 1984, she released Na 'Hes Kardia (\"If You Had a Heart\"). The album was certified gold. The following year her seventh album Kati Simveni (\"Something Is Happening\") was released which included one of her most famous songs, titled \"Dodeka\" [\"Twelve (O'Clock)\"] and reached gold status selling 80.000 units. In 1986 I Epomeni Kinisi (\"The Next Move\") was released. The album included the hit Pragmata (\"Things\") and went platinum, becoming the best selling record of the year. In February 1988 she released her ninth album Tora (\"Now\") and in December the album Empnefsi! (\"Inspiration!\") which went gold. In 1988, she made her debut as a radio producer on ANT1 Radio. Her radio program was titled after one of her songs Ta Koritsia Einai Atakta (\"Girls Are Naughty\") and was aired every weekend. In the same year, she participated with the song Klaio (\"I'm Crying\") at the Greek National Final for Eurovision Song Contest, finishing third. In 1989, she released the highly successful studio album Fotia (Fire), being one of the first albums to feature western sounds. The lead single Pseftika (\"Fake\") became a big hit and the album reached platinum status, selling 180.000 copies and becoming the second best selling record of 1990. She performed at \"Diogenis Palace\" in that same year, Athens's biggest nightclub/music hall at the time. CANNOTANSWER",
          "qas": [
            {
              "followup": "y",
              "yesno": "y",
              "question": "did she have any other famous songs?",
              "answers": [
                {
                  "text": "In 1986 I Epomeni Kinisi (\"The Next Move\") was released.",
                  "answer_start": 992
                },
                {
                  "text": "Epomeni Kinisi (\"The Next Move\") was released.",
                  "answer_start": 1002
                },
                {
                  "text": "Pragmata (\"Things\")",
                  "answer_start": 1076
                },
                {
                  "text": "The album included the hit Pragmata (\"Things\") and went platinum,",
                  "answer_start": 1049
                }
              ],
              "id": "C_5ab583f64dbb47b995cf59328ea0af43_1_q#7",
              "orig_answer": {
                "text": "The album included the hit Pragmata (\"Things\") and went platinum,",
                "answer_start": 1049
              }
            }
          ],
          "id": "C_5ab583f64dbb47b995cf59328ea0af43_1"
        }
      ],
      "section_title": "1983-1989: Collaboration with Nikos Karvelas",
      "background": "Anna Vissi (Greek: Anna Bisse (pronounced ['ana 'visi], locally ['an:a 'viS:i]); born 20 December 1957), also known as Anna Vishy, is a Greek Cypriot singer, songwriter, actress, television presenter, radio personality, and businesswoman.",
      "title": "Anna Vissi"
    }
  ]
}
```   
-   [DuoRC - Eng](https://duorc.github.io/)
```   
[
 {
  "plot": "South Boston teenager Jason Tripitikas is a fan of martial arts films and awakens from a dream of a battle between the Monkey King and celestial soldiers in the clouds. He visits a pawn shop in Chinatown to buy Wuxia DVDs and discovers a golden staff. On his way home, Tripitikas is harassed by some hooligans, whose leader Lupo attempts to use him to help them rob the shop-owner Hop, who is shot by Lupo. Hop tells Tripitikas to deliver the staff to its rightful owner and Tripitikas flees with the staff. He is cornered on the rooftop before being pulled off the roof by the staff.\nWhen Tripitikas regains consciousness, he finds himself in a village in ancient China that is under attack by armored soldiers. The soldiers see his staff and attempt to seize it. He is saved by the inebriated traveling scholar Lu Yan, a supposed \"immortal,\" who remains alert and agile even when drunk. Lu tells him the story of the rivalry between the King and the Jade Warlord. The Warlord tricked the King into setting aside his magic staff, Ruyi Jingu Bang, and transformed the immortal into a stone statue, but the King cast his staff far away before the transformation. Lu ends the tale with a prophecy about a \"Seeker\" who will find the staff and free the King. Just then, they are attacked by the Warlord's men again, but manage to escape with the help of Golden Sparrow, a young woman. She reveals that her family was murdered by the Warlord, against whom she has sworn revenge.\nMeanwhile, the Warlord, upon learning about the staff, sends the witch Ni-Chang to help him retrieve it in exchange for the elixir of immortality. Tripitikas, Lu and Sparrow meet a strange man dressed in white who takes the staff away from them. Lu fights with the man (later revealed to be the Silent Monk) for the staff until the latter realizes that Tripitikas is the Seeker, and joins them in their quest to free the King. As the four travel to Five Elements Mountain, Lu and the Monk teach Tripitikas kung fu along the way. After crossing a desert, they encounter Ni-Chang and her henchmen and a battle ensues, in which Lu is mortally wounded. Tripitikasâs team takes refuge in a monastery, where they learn that Lu is actually not an immortal as he failed the test, and only the Warlordâs elixir can save his life. In desperation, Tripitikas goes to the Warlord's palace alone to exchange the staff for the elixir.\nThe Warlord asks Tripitikas to duel Ni-Chang to death, since the former can give the elixir to only one of them. Tripitikas is overpowered until his teammates and monks from the monastery arrive to join the battle. Tripitikas manages to grab the elixir and tosses it to Lu, who drinks it and recovers. The Monk passes the staff to Tripitikas, who uses it to smash the King's statue. The King is freed and the Monk is revealed to be actually one of the King's clones. Lu kills Ni-Chang. After another long battle between the King and the Warlord, the latter is eventually stabbed by Tripitikas and falls into a lava pit to his death. However, Sparrow succumbs to her wounds. The Jade Emperor, having returned from his meditation, praises Tripitikas for fulfilling the prophecy and allows him for one wish, which he asks to return home.\nTripitikas finds himself back in the present. He overpowers Lupo and drives the other hooligans away. Hop survives from the wound and claims that he is immortal (hinting that he is actually Lu). Before the film ends, Jason is delighted to meet a woman who resembles Sparrow. Tripitikas continues honing his kung fu skills while Lu narrates the Kingâs search for truth.\n",
  "title": "The Forbidden Kingdom",
  "qa": [
   {
    "id": "eebdf531-16e1-7bb2-c7ae-4d08c5e0bd42",
    "question": "Who drinks the elixir?",
    "answers": [
     "Lu"
    ],
    "no_answer": false
   }
  ],
  "id": "/m/0gj6pd"
 }
]
```   
-   [Drop - Eng](https://allennlp.org/drop)
```   
{
  "nfl_1184": {
    "passage": " Hoping to rebound from their loss to the Patriots, the Raiders stayed at home for a Week 16 duel with the Houston Texans.  Oakland would get the early lead in the first quarter as quarterback JaMarcus Russell completed a 20-yard touchdown pass to rookie wide receiver Chaz Schilens.  The Texans would respond with fullback Vonta Leach getting a 1-yard touchdown run, yet the Raiders would answer with kicker Sebastian Janikowski getting a 33-yard and a 30-yard field goal.  Houston would tie the game in the second quarter with kicker Kris Brown getting a 53-yard and a 24-yard field goal. Oakland would take the lead in the third quarter with wide receiver Johnnie Lee Higgins catching a 29-yard touchdown pass from Russell, followed up by an 80-yard punt return for a touchdown.  The Texans tried to rally in the fourth quarter as Brown nailed a 40-yard field goal, yet the Raiders' defense would shut down any possible attempt.",
    "qa_pairs": [
      {
        "question": "Who scored the first touchdown of the game?",
        "answer": {
          "number": "",
          "date": {
            "day": "",
            "month": "",
            "year": ""
          },
          "spans": [
            "Chaz Schilens"
          ]
        },
        "query_id": "f37e81fa-ef7b-4583-b671-762fc433faa9",
        "validated_answers": [
          {
            "number": "",
            "date": {
              "day": "",
              "month": "",
              "year": ""
            },
            "spans": [
              "Chaz Schilens"
            ]
          },
          {
            "number": "",
            "date": {
              "day": "",
              "month": "",
              "year": ""
            },
            "spans": [
              "JaMarcus Russell"
            ]
          }
        ]
      }
    ],
    "wiki_url": "https://en.wikipedia.org/wiki/Earl's_Court"
  }
}
```   
-   [MLQA - Multi-Lang](https://github.com/facebookresearch/MLQA)
```   
{
  "version": 1,
  "data": [
    {
      "title": "एडगर ऍलन पो",
      "paragraphs": [
        {
          "context": "पो ने फिर गद्य की तरफ ध्यान दिया और अगले कई साल साहित्यिक पत्रिकाओं में आलोचक की तरह काम किया। ये अपनी निराली आलोचना शैली के लिए बहुत प्रसिद्ध हुए। इस दौरान ये बाल्टीमोर, फिलाडेल्फिया और न्यू यार्क के बीच काफी घूमे। १८३५ में बाल्टीमोर में इनका विवाह दूर की रिश्तेदार १३ साल की वर्जीनिया क्लेम से हुआ, लेकिन ये कुछ ही वर्ष बाद तपेदिक के कारण चल बसीं। जनवरी १८४५ में पो ने द रेवन (अंग्रेजी: The Raven, काला कौवा) नाम की कविता प्रकाशित की, जो काफी प्रसिद्ध हुई। इन्होंने अपनी खुद की पत्रिका \"द पेन्न\" (अंग्रेजी: The Penn) प्रकाशित करने की तैयारी शुरु की, लेकिन इसके प्रकाशित होने से पहले ही इनकी मृत्यु हो गई। इनकी मृत्यु बाल्टीमोर में ४० साल की आयु में हुई, लेकिन कारण अभी तक नहीं पता चल पाया है। इतिहासकारों ने शराब, मस्तिष्क की सूजन, हैजा, नशीली दवाएँ, हृदय रोग इत्यादि से लेकर रेबीज़, तपेदिक आदि के बारे में अटकलें लगाई हैं।",
          "qas": [
            {
              "id": "2e62cb1a941e40208fe73d1d11d77611f8fc91af",
              "question": "这项工作最初的计划名称是什么？",
              "answers": [
                {
                  "text": "द पेन्न",
                  "answer_start": 489
                }
              ]
            }
          ]
        }
      ]
    }
  ]
}
```   
-   [MRQA - Eng(Multi-Dataset)](https://github.com/mrqa/MRQA-Shared-Task-2019)
```   
{
  "header": {
    "dataset": <dataset name>,
    "split": <train|dev|test>,
  }
}
...
{
  "context": <context text>,
  "context_tokens": [(token_1, offset_1), ..., (token_l, offset_l)],
  "qas": [
    {
      "qid": <uuid>,
      "question": <question text>,
      "question_tokens": [(token_1, offset_1), ..., (token_q, offset_q)],
      "detected_answers": [
        {
          "text": <answer text>,
          "char_spans": [[<start_1, end_1>], ..., [<start_n, end_n>]],
          "token_spans": [[<start_1, end_1>], ..., [<start_n, end_n>]],
        },
        ...
      ],
      "answers": [<answer_text_1>, ..., <answer_text_m>]
    },
    ...
  ]
}
```   
-   [MultiQA - Eng(Multi-Dataset)](https://github.com/alontalmor/MultiQA)
```   
{
 "id": "SQuAD_ba1f039e847c4fbd8930955effd64999",
 "context": {
  "documents": [
   {
    "text": "Anti-inflammatory drugs are often used to control the effects of inflammation. Glucocorticoids are the most powerful of these drugs; however, these drugs can have many undesirable side effects, such as central obesity, hyperglycemia, osteoporosis, and their use must be tightly controlled. Lower doses of anti-inflammatory drugs are often used in conjunction with cytotoxic or immunosuppressive drugs such as methotrexate or azathioprine. Cytotoxic drugs inhibit the immune response by killing dividing cells such as activated T cells. However, the killing is indiscriminate and other constantly dividing cells and their organs are affected, which causes toxic side effects. Immunosuppressive drugs such as cyclosporin prevent T cells from responding to signals correctly by inhibiting signal transduction pathways.",
    "title": "Immune_system",
    "tokens": {
     "title": [
      [
       "Immune_system",
       0
      ]
     ],
     "text": [
      [
       "Anti",
       0
      ],
      [
       "-",
       4
      ]
     ]
    }
   }
  ]
 },
 "qas": [
  {
   "qid": "SQuAD_q_572a03086aef0514001551a2",
   "question": "What are the most powerful class of anti-inflammatory drugs?",
   "answers": {
    "open-ended": {
     "annotators_answer_candidates": [
      {
       "single_answer": {
        "extractive": {
         "answer": "Glucocorticoids",
         "instances": [
          {
           "doc_id": 0,
           "part": "text",
           "start_byte": 79,
           "text": "Glucocorticoids",
           "token_inds": [
            14,
            14
           ]
          }
         ]
        }
       }
      },
      {
       "single_answer": {
        "extractive": {
         "answer": "Glucocorticoids",
         "instances": [
          {
           "doc_id": 0,
           "part": "text",
           "start_byte": 79,
           "text": "Glucocorticoids",
           "token_inds": [
            14,
            14
           ]
          }
         ]
        }
       }
      },
      {
       "single_answer": {
        "extractive": {
         "answer": "Glucocorticoids",
         "instances": [
          {
           "doc_id": 0,
           "part": "text",
           "start_byte": 79,
           "text": "Glucocorticoids",
           "token_inds": [
            14,
            14
           ]
          }
         ]
        }
       }
      }
     ]
    }
   },
   "question_tokens": [
    [
     "What",
     0
    ],
    [
     "are",
     5
    ]
   ]
  }
 ]
}
```   

### User log
-   [MSMARCO - Eng](http://www.msmarco.org/) 
```   
{
	"answers":["A corporation is a company or group of people authorized to act as a single entity and recognized as such in law."],
	"passages":[
		{
			"is_selected":0,
			"url":"http:\/\/www.wisegeek.com\/what-is-a-corporation.htm",
			"passage_text":"A company is incorporated in a specific nation, often within the bounds of a smaller subset of that nation, such as a state or province. The corporation is then governed by the laws of incorporation in that state. A corporation may issue stock, either private or public, or may be classified as a non-stock corporation. If stock is issued, the corporation will usually be governed by its shareholders, either directly or indirectly."},
		...
		}],
	"query":". what is a corporation?",
	"query_id":1102432,
	"query_type":"DESCRIPTION",
	"wellFormedAnswers":"[]"
}
```   
-   [DuReader - Simplified-Chi](https://github.com/baidu/DuReader) 
```   
{
 "is_selected": true,
 "title": "截至和截止有什么区别_百度知道",
 "most_related_para": 0,
 "segmented_title": [
  "截至",
  "和",
  "截止",
  "有",
  "什么",
  "区别",
  "_",
  "百度",
  "知道"
 ],
 "segmented_paragraphs": [
  [
   "截止",
   ":",
   "是",
   "到",
   "某",
   "期限",
   "停止",
   ";",
   "截至",
   ":",
   "是",
   "停止",
   "于",
   "某",
   "期限",
   ".",
   "如",
   ":",
   "这",
   "项",
   "工作",
   "到",
   "今年",
   "六月份",
   "截止",
   ".",
   "　　",
   "这",
   "项",
   "工作",
   "截至",
   "到",
   "今年六月",
   "分",
   "."
  ]
 ],
 "paragraphs": [
  "截止:是到某期限停止; 截至:是停止于某期限. 如:这项工作到今年六月份截止. 　　这项工作截至到今年六月分."
 ],
 "bs_rank_pos": 1
}
```   
-   [MiningZhiDaoQACorpus - Simplified-Chi](https://github.com/liuhuanyong/MiningZhiDaoQACorpus)
```   
 {
        "_id" : ObjectId("5d36e599bc54f451543da02b"),
        "url" : "http://zhidao.baidu.com/question/2207667243516878988.html",
        "answers" : [
            "这与当时的历史背景有关。卡萨布兰卡属于法国的殖民地，而当时的法国是与纳粹德国合作的。但在法国人中又分为合作和抵抗两派。警长的立场早先是在双方之间摇摆不定。后来与Rick站在了一起。拿酒瓶又扔掉象征其抛弃过去，走上了义无反顾的抵抗道路。----------------------------------------------------------------------------------------卡萨布兰卡的剧情简介   · · · · · · 二战期间，卡萨布兰卡是欧洲逃往美国的必经之地，那里鱼龙混杂，局势紧张。里克（亨佛莱?鲍嘉 Humphrey Bogart 饰）是一个神秘的商人，他在卡萨布兰卡开了一家人气很旺的夜总会，并拥有两张宝贵的通行证。一天，反纳粹人士维克多和妻子伊尔莎（英格丽?褒曼 Ingrid Bergman 饰）来到夜总会，原来他们正在逃避纳粹的追捕。碰巧的是，里克发现，伊尔莎竟然是他的旧日情人。那段爱曾经刻骨铭心，却因为一个误会而终止。而当误会消解时，伊尔莎和里克的感情还是不可避免的重燃了。里克手上的两张通行证能帮助维克多度过难关，但这样一来，伊尔莎是决定留下，还是离去，他们的爱情在政治和伦理的推波逐流中走向何方。"
        ],
        "question" : "卡萨布兰卡为什么是欧洲逃往美国的必经之地",
        "tags" : [
            "美国"
        ]
    }
```   
-   [Triviaqa - Eng](http://nlp.cs.washington.edu/triviaqa/) 
```   
{
  "Data": [
    {
      "Answer": {
        "Aliases": [
          "Sunset Blvd",
          "West Sunset Boulevard",
          "Sunset Boulevard",
          "Sunset Bulevard",
          "Sunset Blvd."
        ],
        "MatchedWikiEntityName": "Sunset Boulevard",
        "NormalizedAliases": [
          "west sunset boulevard",
          "sunset blvd",
          "sunset boulevard",
          "sunset bulevard"
        ],
        "NormalizedMatchedWikiEntityName": "sunset boulevard",
        "NormalizedValue": "sunset boulevard",
        "Type": "WikipediaEntity",
        "Value": "Sunset Boulevard"
      },
      "EntityPages": [
        {
          "DocSource": "TagMe",
          "Filename": "Andrew_Lloyd_Webber.txt",
          "LinkProbability": "0.02934",
          "Rho": "0.22520",
          "Title": "Andrew Lloyd Webber"
        }
      ],
      "Question": "Which Lloyd Webber musical premiered in the US on 10th December 1993?",
      "QuestionId": "tc_33",
      "QuestionSource": "http://www.triviacountry.com/",
      "SearchResults": [
        {
          "Description": "The official website for Andrew Lloyd Webber, ... from the Andrew Lloyd Webber/Jim Steinman musical Whistle ... American premiere on 9th December 1993 at the ...",
          "DisplayUrl": "www.andrewlloydwebber.com",
          "Filename": "35/35_995.txt",
          "Rank": 0,
          "Title": "Andrew Lloyd Webber | The official website for Andrew ...",
          "Url": "http://www.andrewlloydwebber.com/"
        }
      ]
    }
  ],
  "Domain": "Web",
  "VerifiedEval": false,
  "Version": 1.0
}
```   
-   [hotpotqa - Eng](https://hotpotqa.github.io/) 
```   
[
 {
  "_id": "5a8b57f25542995d1e6f1371",
  "answer": "yes",
  "question": "Were Scott Derrickson and Ed Wood of the same nationality?",
  "supporting_facts": [
   [
    "Scott Derrickson",
    0
   ],
   [
    "Ed Wood",
    0
   ]
  ],
  "context": [
   [
    "Adam Collis",
    [
     "Adam Collis is an American filmmaker and actor.",
     " He attended the Duke University from 1986 to 1990 and the University of California, Los Angeles from 2007 to 2010.",
     " He also studied cinema at the University of Southern California from 1991 to 1997.",
     " Collis first work was the assistant director for the Scott Derrickson's short \"Love in the Ruins\" (1995).",
     " In 1998, he played \"Crankshaft\" in Eric Koyanagi's \"Hundred Percent\"."
    ]
   ],
   [
    "Ed Wood (film)",
    [
     "Ed Wood is a 1994 American biographical period comedy-drama film directed and produced by Tim Burton, and starring Johnny Depp as cult filmmaker Ed Wood.",
     " The film concerns the period in Wood's life when he made his best-known films as well as his relationship with actor Bela Lugosi, played by Martin Landau.",
     " Sarah Jessica Parker, Patricia Arquette, Jeffrey Jones, Lisa Marie, and Bill Murray are among the supporting cast."
    ]
   ],
   [
    "Tyler Bates",
    [
     "Tyler Bates (born June 5, 1965) is an American musician, music producer, and composer for films, television, and video games.",
     " Much of his work is in the action and horror film genres, with films like \"Dawn of the Dead, 300, Sucker Punch,\" and \"John Wick.\"",
     " He has collaborated with directors like Zack Snyder, Rob Zombie, Neil Marshall, William Friedkin, Scott Derrickson, and James Gunn.",
     " With Gunn, he has scored every one of the director's films; including \"Guardians of the Galaxy\", which became one of the highest grossing domestic movies of 2014, and its 2017 sequel.",
     " In addition, he is also the lead guitarist of the American rock band Marilyn Manson, and produced its albums \"The Pale Emperor\" and \"Heaven Upside Down\"."
    ]
   ],
   [
    "Doctor Strange (2016 film)",
    [
     "Doctor Strange is a 2016 American superhero film based on the Marvel Comics character of the same name, produced by Marvel Studios and distributed by Walt Disney Studios Motion Pictures.",
     " It is the fourteenth film of the Marvel Cinematic Universe (MCU).",
     " The film was directed by Scott Derrickson, who wrote it with Jon Spaihts and C. Robert Cargill, and stars Benedict Cumberbatch as Stephen Strange, along with Chiwetel Ejiofor, Rachel McAdams, Benedict Wong, Michael Stuhlbarg, Benjamin Bratt, Scott Adkins, Mads Mikkelsen, and Tilda Swinton.",
     " In \"Doctor Strange\", surgeon Strange learns the mystic arts after a career-ending car accident."
    ]
   ],
   [
    "Hellraiser: Inferno",
    [
     "Hellraiser: Inferno (also known as Hellraiser V: Inferno) is a 2000 American horror film.",
     " It is the fifth installment in the \"Hellraiser\" series and the first \"Hellraiser\" film to go straight-to-DVD.",
     " It was directed by Scott Derrickson and released on October 3, 2000.",
     " The film concerns a corrupt detective who discovers Lemarchand's box at a crime scene.",
     " The film's reviews were mixed."
    ]
   ],
   [
    "Sinister (film)",
    [
     "Sinister is a 2012 supernatural horror film directed by Scott Derrickson and written by Derrickson and C. Robert Cargill.",
     " It stars Ethan Hawke as fictional true-crime writer Ellison Oswalt who discovers a box of home movies in his attic that puts his family in danger."
    ]
   ],
   [
    "Deliver Us from Evil (2014 film)",
    [
     "Deliver Us from Evil is a 2014 American supernatural horror film directed by Scott Derrickson and produced by Jerry Bruckheimer.",
     " The film is officially based on a 2001 non-fiction book entitled \"Beware the Night\" by Ralph Sarchie and Lisa Collier Cool, and its marketing campaign highlighted that it was \"inspired by actual accounts\".",
     " The film stars Eric Bana, Édgar Ramírez, Sean Harris, Olivia Munn, and Joel McHale in the main roles and was released on July 2, 2014."
    ]
   ],
   [
    "Woodson, Arkansas",
    [
     "Woodson is a census-designated place (CDP) in Pulaski County, Arkansas, in the United States.",
     " Its population was 403 at the 2010 census.",
     " It is part of the Little Rock–North Little Rock–Conway Metropolitan Statistical Area.",
     " Woodson and its accompanying Woodson Lake and Wood Hollow are the namesake for Ed Wood Sr., a prominent plantation owner, trader, and businessman at the turn of the 20th century.",
     " Woodson is adjacent to the Wood Plantation, the largest of the plantations own by Ed Wood Sr."
    ]
   ],
   [
    "Conrad Brooks",
    [
     "Conrad Brooks (born Conrad Biedrzycki on January 3, 1931 in Baltimore, Maryland) is an American actor.",
     " He moved to Hollywood, California in 1948 to pursue a career in acting.",
     " He got his start in movies appearing in Ed Wood films such as \"Plan 9 from Outer Space\", \"Glen or Glenda\", and \"Jail Bait.\"",
     " He took a break from acting during the 1960s and 1970s but due to the ongoing interest in the films of Ed Wood, he reemerged in the 1980s and has become a prolific actor.",
     " He also has since gone on to write, produce and direct several films."
    ]
   ],
   [
    "The Exorcism of Emily Rose",
    [
     "The Exorcism of Emily Rose is a 2005 American legal drama horror film directed by Scott Derrickson and starring Laura Linney and Tom Wilkinson.",
     " The film is loosely based on the story of Anneliese Michel and follows a self-proclaimed agnostic who acts as defense counsel (Linney) representing a parish priest (Wilkinson), accused by the state of negligent homicide after he performed an exorcism."
    ]
   ]
  ],
  "type": "comparison",
  "level": "hard"
 }
]
```   
-   [CoQA - Eng](https://stanfordnlp.github.io/coqa/) 
```   
{
 "version": "1.0",
 "data": [
  {
   "source": "mctest",
   "id": "3dr23u6we5exclen4th8uq9rb42tel",
   "filename": "mc160.test.41",
   "story": "Once upon a time, in a barn near a farm house, there lived a little white kitten named Cotton. Cotton lived high up in a nice warm place above the barn where all of the farmer's horses slept. But Cotton wasn't alone in her little home above the barn, oh no. She shared her hay bed with her mommy and 5 other sisters. All of her sisters were cute and fluffy, like Cotton. But she was the only white one in the bunch. The rest of her sisters were all orange with beautiful white tiger stripes like Cotton's mommy. Being different made Cotton quite sad. She often wished she looked like the rest of her family. So one day, when Cotton found a can of the old farmer's orange paint, she used it to paint herself like them. When her mommy and sisters found her they started laughing. \n\n\"What are you doing, Cotton?!\" \n\n\"I only wanted to be more like you\". \n\nCotton's mommy rubbed her face on Cotton's and said \"Oh Cotton, but your fur is so pretty and special, like you. We would never want you to be any other way\". And with that, Cotton's mommy picked her up and dropped her into a big bucket of water. When Cotton came out she was herself again. Her sisters licked her face until Cotton's fur was all all dry. \n\n\"Don't ever do that again, Cotton!\" they all cried. \"Next time you might mess up that pretty white fur of yours and we wouldn't want that!\" \n\nThen Cotton thought, \"I change my mind. I like being special\".",
   "questions": [
    {
     "input_text": "What color was Cotton?",
     "turn_id": 1
    }
   ],
   "answers": [
    {
     "span_start": 59,
     "span_end": 93,
     "span_text": "a little white kitten named Cotton",
     "input_text": "white",
     "turn_id": 1
    }
   ],
   "additional_answers": {
    "0": [
     {
      "span_start": 68,
      "span_end": 93,
      "span_text": "white kitten named Cotton",
      "input_text": "white",
      "turn_id": 1
     },
     {
      "span_start": 17,
      "span_end": 93,
      "span_text": " in a barn near a farm house, there lived a little white kitten named Cotton",
      "input_text": "in a barn",
      "turn_id": 2
     },
     {
      "span_start": 192,
      "span_end": 215,
      "span_text": "But Cotton wasn't alone",
      "input_text": "no",
      "turn_id": 3
     },
     {
      "span_start": 258,
      "span_end": 315,
      "span_text": "She shared her hay bed with her mommy and 5 other sisters",
      "input_text": "her mommy and 5 other sisters",
      "turn_id": 4
     },
     {
      "span_start": 416,
      "span_end": 490,
      "span_text": "The rest of her sisters were all orange with beautiful white tiger stripes",
      "input_text": "orange with white tiger stripes",
      "turn_id": 5
     },
     {
      "span_start": 512,
      "span_end": 549,
      "span_text": "Being different made Cotton quite sad",
      "input_text": "no",
      "turn_id": 6
     },
     {
      "span_start": 678,
      "span_end": 716,
      "span_text": "she used it to paint herself like them",
      "input_text": "she painted herself",
      "turn_id": 7
     },
     {
      "span_start": 655,
      "span_end": 676,
      "span_text": "farmer's orange paint",
      "input_text": "the farmer's",
      "turn_id": 8
     },
     {
      "span_start": 718,
      "span_end": 777,
      "span_text": "When her mommy and sisters found her they started laughing.",
      "input_text": "they started laughing",
      "turn_id": 9
     },
     {
      "span_start": 1059,
      "span_end": 1097,
      "span_text": "dropped her into a big bucket of water",
      "input_text": "dropped her into a big bucket of water",
      "turn_id": 10
     },
     {
      "span_start": 1143,
      "span_end": 1171,
      "span_text": "Her sisters licked her face ",
      "input_text": "licked her face",
      "turn_id": 11
     },
     {
      "span_start": 1209,
      "span_end": 1244,
      "span_text": "\"Don't ever do that again, Cotton!\"",
      "input_text": "no",
      "turn_id": 12
     }
    ]
   },
   "name": "mc160.test.41"
  }
 ]
}
```   
-   [QUASAR - Eng](https://github.com/bdhingra/quasar)  
```   
quasar-s/questions
{
 "answer": "php",
 "question": "homestead -- laravel homestead is an official pre-packaged vagrant box that provides you a wonderful development-environment without requiring you to install @placeholder hhvm a web server and any other server software on your local machine.homestead runs on any windows mac or linux system and includes the nginx web server php-5 .6 mysql postgres redis memcached and all of the other goodies you need to develop amazing laravel applications .",
 "uid": "homestead@php@159",
 "tags": [
  "yes-answer-long",
  "yes-answer-short"
 ]
}
quasar-s/contexts
{
  "contexts": [
    [
      62.570347,
      "On mac OS El Capitan I have a virtual-machine vagrant with laravel-homestead box ."
    ]
  ]
}
```   
-   [SearchQA - Eng](https://github.com/nyu-dl/SearchQA)
```   
[
  {
    "category": "HISTORY",
    "air_date": "2004-12-31",
    "question": "'For the last 8 years of his life, Galileo was under house arrest for espousing this man's theory'",
    "value": "$200",
    "answer": "Copernicus",
    "round": "Jeopardy!",
    "show_number": "4680"
  }
]
```   
-   [ComplexWebQuestions - Eng](https://www.tau-nlp.org/compwebq)
```   
[
 {
  "ID": "WebQTest-832_c334509bb5e02cacae1ba2e80c176499",
  "compositionality_type": "composition",
  "created": "2018-02-13T04:12:57",
  "machine_question": "when is the last time the the team has a team moscot named Lou Seal won the world series",
  "question": "Lou Seal is the mascot for the team that last won the World Series when?",
  "sparql": "PREFIX ns: <http://rdf.freebase.com/ns/>\nSELECT DISTINCT ?x\nWHERE {\nFILTER (?x != ?c)\nFILTER (!isLiteral(?x) OR lang(?x) = '' OR langMatches(lang(?x), 'en'))\n?c ns:sports.sports_team.team_mascot ns:m.03_dwn . \n?c ns:sports.sports_team.championships ?x .\n?x ns:time.event.start_date ?sk0 .\n}\nORDER BY DESC(xsd:datetime(?sk0))\nLIMIT 1\n",
  "webqsp_ID": "WebQTest-832",
  "webqsp_question": "when is the last time the giants won the world series"
 }
]
```   
-   [TF 2.0 QA - Eng](https://www.kaggle.com/c/tensorflow2-question-answering)
```   
{
 "example_id": "8777415633185303067",
 "question_text": "the office episode when they sing to michael",
 "document_text": "Michael 's Last Dundies - wikipedia <H1> Michael 's Last Dundies </H1> <P> </P> 21st episode of the seventh season of The Office <Table> <Tr> <Th_colspan=\"2\"> `` Michael 's Last Dundies '' </Th> </Tr> <Tr> <Td_colspan=\"2\"> The Office episode </Td> </Tr> <Tr> <Th> Episode no . </Th> <Td> Season 7 Episode 21 </Td> </Tr> <Tr> <Th> Directed by </Th> <Td> Mindy Kaling </Td> </Tr> <Tr> <Th> Written by </Th> <Td> Mindy Kaling </Td> </Tr> <Tr> <Th> Production code </Th> <Td> 7021 </Td> </Tr> <Tr> <Th> Original air date </Th> <Td> April 21 , 2011 </Td> </Tr> <Tr> <Th> Running time </Th> <Td> 22 minutes </Td> </Tr> <Tr> <Th_colspan=\"2\"> Guest appearance ( s ) </Th> </Tr> <Tr> <Td_colspan=\"2\"> <Ul> <Li> Will Ferrell as Deangelo Vickers </Li> <Li> Jack Coleman as State Sen. Robert Lipton </Li> </Ul> </Td> </Tr> <Tr> <Th_colspan=\"2\"> Episode chronology </Th> </Tr> <Tr> <Td_colspan=\"2\"> ......",
 "long_answer_candidates": [
  {
   "end_token": 190,
   "start_token": 23,
   "top_level": true
  },
  {
   "end_token": 34,
   "start_token": 24,
   "top_level": false
  }
 ]
}
```   
-   [bAbI - Eng](https://github.com/facebook/bAbI-tasks)
```   
ID text
ID text
ID text
ID question[tab]answer[tab]supporting fact IDS.
```   
-   [Physical IQA - Eng](https://leaderboard.allenai.org/physicaliqa/submissions/public)
```   
{
 "id": "f6be5fcc-d686-4549-8207-7904068693d7",
 "goal": "When boiling butter, when it's ready, you can",
 "sol1": "Pour it onto a plate",
 "sol2": "Pour it into a jar"
}
```   
-   [CKBQA - Simplified-Chi](https://github.com/pkumod/CKBQA)
```    
[
q1546:列出中国曾获柏林国际电影节金熊奖的导演？
select ?x where { ?x <职业> <导演>. ?x <国籍> <中华人民共和国>. ?x <主要成就> "威尼斯国际电影节金狮奖". }
<张艺谋><贾樟柯>
]
```    

-----
### Contributing
Have anything in mind that you think is awesome and would fit in this list? Feel free to send a [pull request](https://github.com/voidful/awesome-reading-comprehension-dataset). 

-----
## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

ctw_li = {}
cts_li = {}
cts = {
    1:["Every one of the shirts has a green collar.","Every one of the shirts have a green collar."],
    2:["This singer, along with a few others, play the harmonica on stage.","This singer, along with a few others, plays the harmonica on stage."],
    3:["Sandals and towels are essential gear for a trip to the beach.","Sandals and towels is essential gear for a trip to the beach."],
    4:["The president or the vice president are speaking today.","The president or the vice president is speaking today."],
    5:["Either Cassie or Marie pays the employees this afternoon.","Either Cassie or Marie pay the employees this afternoon."],
    6:["Either the sculpture or the paintings are in the museum today.","Either the sculpture or the paintings is in the museum today."],
    7:["The coat or the hats are in that closet.","The coat or the hats is in that closet."],
    8:["Each of the dancers twirls brilliantly.","Each of the dancers twirl brilliantly."],
    9:["Mustard greens are my favorite vegetable.","Mustard greens is my favorite vegetable."],
    10:["Everybody at the party was enjoying the food.","Everybody at the party were enjoying the food."]
}
def choose_the_word(question,answers,answer):
    for i in answers:
        answers[answers.index(i)] = i.lower()
    print (question)
    while True:
        ans = input()
        if ans.lower() in answers:
            print ("Continue.\n")
            break
        else:
            print ("Choose again. Check the spelling!")
    if ans.lower() != answer.lower():
        ctw_li[question] = [answer,ans]
def choose_the_sentence(no,questions,answer):
    print (questions[0])
    print (questions[1])
    while True:
        ans = input()
        if ans in ["1","2"]:
            print ("Continue.\n")
            break
        else:
            print ("Choose again. Only choose 1 or 2!")
    if ans != answer:
        cts_li[no] = [answer,ans]
print ("Choose the correct word. Check the spelling!")
print ("Total: 21 questions.")
print ("\n")
choose_the_word("Annie and her brothers (is, are) at school.",["is","are"],"are")
choose_the_word("Either my mother or my father (is, are) coming to the meeting.",["is","are"],"is")
choose_the_word("The dog or the cats (is, are) outside.",["is","are"],"are")
choose_the_word("Either my shoes or your coat (is, are) always on the floor.",["is","are"],"is")
choose_the_word("George and Tamara (doesn't, don't) want to see that movie.",["doesn't","don't"],"don't")
choose_the_word("Benito (doesn't, don't) know the answer.",["doesn't","don't"],"doesn't")
choose_the_word("One of my sisters (is, are) going on a trip to France.",["is","are"],"is")
choose_the_word("The man with all the birds (live, lives) on my street.",["live","lives"],"lives")
choose_the_word("The movie, including all the previews, (take, takes) about two hours to watch.",["take","takes"],"takes")
choose_the_word("The players, as well as the captain, (want, wants) to win.",["want","wants"],"want")
choose_the_word("Either answer (is, are) acceptable.",["is","are"],"is")
choose_the_word("Every one of those books (is, are) fiction.",["is","are"],"is")
choose_the_word("Nobody (know, knows) the trouble I've seen.",["know","knows"],"knows")
choose_the_word("(Is, Are) the news on at five or six?",["Is","Are"],"Is")
choose_the_word("Eight dollars (is, are) the price of a movie these days.",["is","are"],"is")
choose_the_word("(Is, Are) the tweezers in this drawer?",["Is","Are"],"Are")
choose_the_word("Your pants (is, are) at the cleaner's.",["is","are"],"are")
choose_the_word("The committee (debates, debate) these questions carefully.",["debates","debate"],"debates")
choose_the_word("The committee members (leads, lead) very different lives in private.",["leads","lead"],"lead")
choose_the_word("The Prime Minister, together with his wife, (greets, greet) the press cordially.",["greets","greet"],"greets")
choose_the_word("All of the CDs, even the scratched one, (is, are) in this case.",["is","are"],"are")
if len(ctw_li) == 0:
    print ("Perfect! You got every question right!")
else:
    print ("You got " + str(len(ctw_li)) + " questions wrong.")
    print ("\n")
    for i in ctw_li:
        print ("Question: " + i)
        print ("Correct Answer: " + ctw_li[i][0])
        print ("Your Answer: " + ctw_li[i][1])
        print ("\n \n")

print ("\n")
print ("Choose the correct sentence.")
print ("Input 1 or 2.")
print ("Total: 10 questions.")
choose_the_sentence(1,["Every one of the shirts has a green collar.","Every one of the shirts have a green collar."],"1")
choose_the_sentence(2,["This singer, along with a few others, play the harmonica on stage.","This singer, along with a few others, plays the harmonica on stage."],"2")
choose_the_sentence(3,["Sandals and towels are essential gear for a trip to the beach.","Sandals and towels is essential gear for a trip to the beach."],"1")
choose_the_sentence(4,["The president or the vice president are speaking today.","The president or the vice president is speaking today."],"2")
choose_the_sentence(5,["Either Cassie or Marie pays the employees this afternoon.","Either Cassie or Marie pay the employees this afternoon."],"1")
choose_the_sentence(6,["Either the sculpture or the paintings are in the museum today.","Either the sculpture or the paintings is in the museum today."],"1")
choose_the_sentence(7,["The coat or the hats are in that closet.","The coat or the hats is in that closet."],"1")
choose_the_sentence(8,["Each of the dancers twirls brilliantly.","Each of the dancers twirl brilliantly."],"1")
choose_the_sentence(9,["Mustard greens are my favorite vegetable.","Mustard greens is my favorite vegetable."],"1")
choose_the_sentence(10,["Everybody at the party was enjoying the food.","Everybody at the party were enjoying the food."],"1")
if len(cts_li) == 0:
    print ("Perfect! You got every question correct!")
else:
    print ("You got " + str(len(cts_li)) + " questions wrong.")
    print ("\n")
    for i in cts_li:
        print ("Choices: ")
        print (cts[i][0])
        print (cts[i][1])
        print ("Correct Answer: " + cts_li[i][0])
        print ("Your Answer: " + cts_li[i][1])
        print ("\n \n")

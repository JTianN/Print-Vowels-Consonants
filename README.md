function vowelsAndConsonants(s) {
    const vowels = ['a', 'e', 'i', 'o', 'u'];
    var letters = s.split('');
    var vowelsFound = [];
    var consonantsFound = [];

    for (var i in letters) {
        if (vowels.includes(letters[i])) {
            vowelsFound.push(letters[i]);
        } else {
            consonantsFound.push(letters[i]);
        }
    }
//Prints the vowels in their order, on a new line for each character.
    console.log(vowelsFound.join('\n'));
    console.log(consonantsFound.join('\n'));
}

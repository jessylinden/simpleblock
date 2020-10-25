# simpleblock
var square = {
    bg: {
        src: 'background.jpg
    }
};
simpleblock.addEventlistener('loaded', function () {
    simpleblock.introscreen = BLOCKS.introScreen(square, simpleblock);
})
simpleblock.load()

BLOCKS.debug('hello')


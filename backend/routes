const express = require('express');
const router = express.Router();

router.get('/tweets', (req, res) => {
    const str = [
        {
            "name": "Codr Kai",
            "msg": "This is my first tweet!",
            "username": "codrkai"
        },
        {
            "name": "Samantha K",
            "msg": "React JS is so simple!",
            "username": "samanthakai"
        },
        {
            "name": "John Doe",
            "msg": "Sweep the leg!",
            "username": "johnk"
        }
    ];
    res.end(JSON.stringify(str));
});

router.post('/addTweet', (req, res) => {
    res.end('NA');
});

module.exports = router;

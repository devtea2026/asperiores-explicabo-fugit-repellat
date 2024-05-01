[![Build Status](https://travis-ci.org/unsegnor/@devtea2026/asperiores-explicabo-fugit-repellat.svg?branch=master)](https://travis-ci.org/unsegnor/@devtea2026/asperiores-explicabo-fugit-repellat)

# @devtea2026/asperiores-explicabo-fugit-repellat
Just a method to expect an async method to throw

~~~~
const expectToThrow = require('@devtea2026/asperiores-explicabo-fugit-repellat')

describe('some method', function(){
    it('must throw', async function(){
        await expectToThrow(async function(){
            await someMethod()
        })
    })
})
~~~~
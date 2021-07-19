#!/usr/bin/ruby

class Giantess
    def initialize(name, shoe, cruel)
        @name = name
        @footwear = shoe
        @cruelty = cruel
        @IsBored = true
        if @cruelty >= 50
            @IsCruel = true
        else
            @IsCruel = false
        end
    end
    def NoticeTiny
        puts "#@name notices a tiny."
        if @IsBored
            puts "She is bored, so..."
            if @IsCruel
                puts "She raises her #@footwear. The tiny's fate is imminent."
                @IsBored = false
            else
                puts "The tiny may enjoy themselves for a while."
                if rand(2) > 1
                    @IsBored = true
                else
                    @IsBored = false
                end
            end
        else
            puts "She doesn't care, so the tiny is ignored."
            @IsBored = true
        end
    end
end
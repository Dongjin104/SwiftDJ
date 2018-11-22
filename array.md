# SwiftDJ

중복 이 없는 배열에서 하나 이상의 임의의 요소를 가져올 수 있기를 원하면 GameplayKit에서 다룹니다.
import GameplayKit
let array = ["one", "two", "three", "four"]

let shuffled = GKMersenneTwisterRandomSource.sharedRandom().arrayByShufflingObjects(in: array)

let firstRandom = shuffled[0]
let secondRandom = shuffled[1]

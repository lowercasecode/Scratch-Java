import {
  Project,
  Sprite
} from "https://unpkg.com/leopard@^1/dist/index.esm.js";

import Stage from "./Stage/Stage.js";
import B from "./B/B.js";
import Pen from "./Pen/Pen.js";
import Sprite1 from "./Sprite1/Sprite1.js";

const stage = new Stage({ costumeNumber: 1 });

const sprites = {
  B: new B({
    x: 36,
    y: 28,
    direction: 90,
    rotationStyle: Sprite.RotationStyle.ALL_AROUND,
    costumeNumber: 1,
    size: 100,
    visible: true,
    layerOrder: 1
  }),
  Pen: new Pen({
    x: 240,
    y: -180,
    direction: 70.31822912999999,
    rotationStyle: Sprite.RotationStyle.ALL_AROUND,
    costumeNumber: 1,
    size: 100,
    visible: true,
    layerOrder: 2
  }),
  Sprite1: new Sprite1({
    x: 0,
    y: -11.8865778258,
    direction: 70.31822912999999,
    rotationStyle: Sprite.RotationStyle.ALL_AROUND,
    costumeNumber: 1,
    size: 100,
    visible: true,
    layerOrder: 3
  })
};

const project = new Project(stage, sprites, {
  frameRate: 30 // Set to 60 to make your project run faster
});
export default project;

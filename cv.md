# Oleksander Soldatov

- Contacts
  - archylexx@gmail.com
  - https://t.me/archy-fake
  
I want to make the world a better place. Freedom makes a human creative and the less routine work, the more time for creativity. Also, working in an industrial plant, there is a risk of injury at work, but this can be avoided by remote control of robot-manipulators. One solution is networks and artificial intelligence. I have passion for technology and ability to learn fast.
  
- Skills
  - C/C++
  - Java
  - JavaScript
  - HTML/CSS
  - Cocos2d-x
  - Git
  - Gradle
  - Android Studio
  - Blender
  - Gimp
  - Krita
  - GNU/Linux
  
*Sample code from arcade game "Frolic":*
```cpp
Vec2 FrolicUtils::rotate_coordinates(Vec2 _point, float _beta, Vec2 _null_point) {
	float x = _point.x * cos(_beta) - _point.y * sin(_beta) + _null_point.x;
	float y = _point.x * sin(_beta) + _point.y * cos(_beta) + _null_point.y;

	return Vec2(x, y);
}

bool FrolicUtils::checkCollision(Sprite *_a, Sprite *_b) {
	if ((_a->getPosition().x + _a->getContentSize().width > _b->getPosition().x - _b->getContentSize().width / 2) &&
	    (_a->getPosition().x - _a->getContentSize().width < _b->getPosition().x + _b->getContentSize().width / 2) &&
	    (_a->getPosition().y > _b->getPosition().y) &&
	    (_a->getPosition().y < _b->getPosition().y + _b->getContentSize().height))
    
		return true;
	
	return false;
}
```

- Experience
  - [Solar system simulator](https://github.com/archylex/Gallex) in Small Academy of Sciences
  - The arcage game [Frolic](https://github.com/archylex/Frolic)
  - The shoot'em'up game [Nebula Psi](https://github.com/archylex/Nebula-Psi)
  - The education game [Arytmetyka](https://github.com/archylex/Arytmetyka)
  - The handbook with quizes [j(S)ensei](https://github.com/archylex/jsensei)
  
- Education
  - Secondary education
  - Uncompleted specialized secondary (painting)
  
- Languages
  - English (simple)
  - Japanese (N3)

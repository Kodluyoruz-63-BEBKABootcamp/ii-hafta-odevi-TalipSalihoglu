# Github da kullanılan lisanslar ve arasındaki farklar nelerdir?
### MGNU
* General Public License
* Kopyalayabilirsiniz.
* Dağıtabilirsiniz.
* İstediğiniz değişiklikleri yapabilirsiniz.

### MIT License
* Yazılımı dağıtabilirsiniz.
* Yazılımı satabilirsiniz ve kaynak kodunu sağlamak zorunda değilsiniz.
* Kaynak kodunu alan herkes değiştirebilir, yeni versiyonlarını yayınlayabilir.
* Ticari olarak kullanabilirsiniz.

### Apache License
* Tüm kopyaları, değiştirilmiş veya değiştirilmemiş, lisansın bir kopyası eşliğinde dağıtılabilir yada kullanılabilir.
* Bütün değişiklikler, değiştirilmiş olarak işaretlenmelidir.
* Ticari olarak kullanabilirsiniz.

### Creative Commons
* Yazılımın yazarı her zaman eklenmelidir. Bunun haricinde kopyalamak, yayınlamak serbesttir.
* Yazılım ticari amaçlarla kullanılamaz.
* Yazılımı değiştiremezsiniz, sadece orjinalini kullanabilirsiniz.

# Merge - Squash-Rebase arasındaki farklar nelerdir?

Merge ile yaptığımız birleştirmede yeni bir commit yaratacak ve yeni branch’deki tüm history tarafını kaybetmeden birleştirme işlemi gerçekleşmiş olcaktır.
Rebase ile birleştirdiğimizde ise branch deki commit’lerimizi tek tek alıp istediğmiz branch üzerine ekleyecektir. Böylelikle tek bir history oluşturacak ve istenmeyen history ortadan kalkacaktır. Aralarında ki fark ise git rebase kullanımında history’nin temizlendiğini ve git merge kullandığımızda ise tüm geçmişin korunduğunu görüyoruz. 
squash komutu aslında farklı bir rebase kullanımı olarak değerlendirilebilir. Geçmişte atılan commit’leri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanılır.


# GOF Nedir?
Eric Gamma, Richard Helm, Ralph Johnson ve John Vlissides 1995’te “Design Patterns : Elements of Reusable Object – Oriented Software” kitabını çıkardılar. Bu dörtlü ayrıca “Gang of Four” olarak da bilinir.“Design pattern” kavramı bir kurallar topluluğundan ziyade bir işi nasıl ve en güzel ne şekilde yapabileceğimiz gösteren yöntemler topluluğudur. Tasarım desenleri tecrübe ile oluşturulan yapılardır. Bazıları olmazsa olmaz yapılar olmasına rağmen bazıları tamamen yazılımın sanatsal yönünü göstermek için tasarlanmıştır.

* Creational
Nesneleri yaratmakta kullanılan 5 adet tasarım kalıbı
* Structural
Nesneler arasındaki yapıları ifade eden ilişkilerden 7 adet tasarım kalıbı
* Behavioral
Nesnelerin çalışma zamanına ait davranışlarını değiştirmek için oluşturulan tasarımlardan 11 adet tasarım kalıbı

Creational Patterns: Singleton, Factory, Abstract Factory, Builder, and Prototype
Structural Patterns: Composite, Decorator, Proxy, Façade, Adaptor, Flyweight, and Bridge
Behavioral Patterns: Strategy, Command, Observer, State, Visitor, Iterator, and Mediator, Template Method, Chain of Responsibility, and Memento

# Interface ve Abstract sınıflar arasındaki farklar nelerdir?
![](https://miro.medium.com/max/661/1*vmQhGSTGAeIIsCX0jEPUqg.jpeg)

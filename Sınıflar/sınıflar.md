## Sınıflar

* Sınıflar Ruby'deki olmazsa olmaz olan yapılardır ayrıca Ruby dili sınıflardan yani türetilen nesnelerden oluşmuştur.

* Sınıfları bazı değerlere atama yapmak için ve gerektiğinde metot çağırmak için kullanabiliriz.

<h3>Örnekler</h3>
<hr width="100%" color="#7026E3" size="5">

<h5>Basit bir sınıf oluşturma</h5>

````ruby
class Sınıfİsmi
	def initialize(name)
		@name = name
	end
end
````

**Burada yaptığımız sınıfa bir bakalım :**

````ruby
class Sınıfİsmi 
````
* <p>Burası ile sınıfımızı <strong>class</strong> anahtar kelimesini kullarak oluşturuyoruz</p>

````ruby
def initialize(name)
	@name = name
end
````

* <p>Burada ise özel bir metot olan <strong>initialize</strong> metodunu çağırıyoruz.<br />Bu metodun özel olmasının sebebi nesne ilk oluşturulurken bu metodun çağırılmasıdır.<br />Göründüğü üzere bu metot <strong>name</strong> adında bir değişken kabul etmiş ve bu değişkene birazdan değineceğimiz <strong>örnek</strong> değişkene atamıştır:<strong>@name = name</strong></p>

**Nesne oluşturma**
* Sınıflardan nesne oluşturmak en az sınıf oluşturmak kadar kolaydır:

````ruby
nesne = Sınıfİsmi.new(name:"Ruby")
````

<p>Göründüğü üzere sınıf üzerinde nesne oluşturmak için <strong>new</strong> anahtar sözcüğünü kullandık ve içine ilk çağırılan metot olan <strong>initialize</strong> metodu için parametre gönderdik.</p>
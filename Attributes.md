# .NET Attributes

- **[Serializable]**: Bir sınıfın serileştirilebilir olduğunu belirtir.

- **[Obsolete]**: Bir sınıf, metod veya özellik artık kullanılmıyorsa bu attribute ile işaretlenir. Kullanıcıyı bu yapının eski olduğunu ve gelecekte kaldırılabileceğini belirtir.
  - Örnek: `[Obsolete("Bu metod yerine YeniMetod'u kullanın.")]`

- **[DllImport]**: Bir dış DLL dosyasındaki bir metodu .NET uygulamasına dahil etmek için kullanılır.
  - Örnek: `[DllImport("user32.dll")]`

- **[TestMethod]**: Bu attribute, birim testlerinde bir metodu test metodu olarak işaretler (MSTest framework'ü ile kullanılır).

- **[Required]**: Bir modeldeki bir alanın zorunlu olduğunu belirtir (özellikle ASP.NET MVC ve Web API projelerinde kullanılır).

- **[Range]**: Bir alanın alabileceği değer aralığını belirtir.
  - Örnek: `[Range(1, 100)]`

- **[Key]**: Bir alanın veritabanındaki birincil anahtar olduğunu belirtir (Entity Framework ile kullanılır).

- **[ForeignKey]**: Bir alanın yabancı anahtar olduğunu belirtir.
  - Örnek: `[ForeignKey("DepartmentId")]`

- **[HttpGet]**: Bir metodu HTTP GET isteğine yanıt verecek şekilde işaretler (ASP.NET Core MVC'de kullanılır).

- **[HttpPost]**: Bir metodu HTTP POST isteğine yanıt verecek şekilde işaretler.

- **[ValidateAntiForgeryToken]**: Form gönderimlerinde CSRF (Cross-Site Request Forgery) saldırılarına karşı koruma sağlar.

- **[Authorize]**: Bir işlemi gerçekleştirmek için kullanıcı yetkilendirmesi gerektiğini belirtir.

- **[DataContract]**: Bir sınıfı veri sözleşmesi olarak işaretler, özellikle WCF (Windows Communication Foundation) servislerinde kullanılır.

- **[DataMember]**: Bir sınıftaki özellik veya alanın veri sözleşmesinin bir parçası olduğunu belirtir.

- **[NonSerialized]**: Bir alanın serileştirilmeyeceğini belirtir.

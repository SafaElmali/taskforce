# VS Code içerisinde Terminal Kullanmadan GIT Temel Komutları


Henüz versiyon kontrolü altında olmayan bir projenin dizininde, boş bir git deposu oluşturmak için **Activity Bar** bölümünden **Source Control** (1) ikonuna tıklayıp, **Initialize Repository** (2) butonuna tıklamalıyız.

![git-init](figures/1-git-init.png)



Yeni eklenen veya üzerinde değişiklik yapılan dosyaları **staged** ortamına göndermek için **Stage Changes** buttonuna tıklamalıyız.



![git-add-1](figures/2-git-add-1.png)



Birden fazla dosyamız olduğu zamanlarda eğer bütün değişiklikleri tek bir seferde **staged** ortamına göndermek istiyorsak **Stage All Changes** buttonuna tıklamalıyız. 


![git-add-2](figures/2-git-add-2.png)



Staged ortamına dosyayı eklediğimizde aşağıdaki resimde olduğu gibi, dosyanın yanında **"A"** (1) *(added)* yazacaktır. Staged ortamına eklemediğimiz dosyalar olursa bu dosyaların yanında da **"U"** (2) *(untracked)* yazacaktır.

![git-status-1](figures/3-git-status-1.png)


*Commit*, **staged** ortamına alınan dosyaların *Local Repository*’e gönderilmesidir.  En iyi uygulama yöntemi her kayıt sırasında yapılan değişiklikleri açıklayıcı bir mesaj eklemektir. Ayrıca her commit benzersiz bir kimliğe (unique ID) sahip olur. Dosyalarımızı commit'lemek için **Message** bölümüne (1) commit'imizi açıklayıcı bir mesaj yazmalıyız ve ardından **Commit** butonuna (2) basmalıyız.

![git-commit](figures/4-git-commit.png)

Commit'lenen dosya üzerinde değişiklik yaptığımızda, dosyanın yanında **"M"** (1) *(modified)* yazacaktır.

![git-status-2](figures/3-git-status-2.png)

Dosyamızda yapılan değişikliği görüntülemek için, Source Control bölümünde, dosyanın üzerine tıkladığımızda (1), iki farklı bölüm karşımıza geliyor. En sağdaki bölümde (3) dosyamızın üzerinde yapığımız değişiklileri görüntüleyebiliriz.


![git-diff](figures/5-git-diff.png)



Bu değişiklikleri eğer geri almak istersek, tekrar sol bölümdeki (2) gibi olmasını istiyorsak **Discard Changes** butonuna tıklamalıyız.


![discard-changes](figures/6-discard-changes.png)



Eğer remote repository'e bağlıysak ve commit'lerimizi remote repository'e göndermek istersek **Views and More Actions** (1) butonuna tıklayıp, **Push** (2) seçeneğini seçmeliyiz.

![git-push](figures/7-git-push.png)

### Sorular

1. Yeni eklenen veya üzerinde değişiklik yapılan dosyaları staged ortamına göndermek için aşağıdaki butonlardan hangisine tıklamalıyız?

- [ ] Discard Changes
- [x] Stage Changes
- [ ] Initialize Repository
- [ ] Views and More Actions

2.Views and More Actions buttonuna tıkladıktan sonra commit'lerimizi remote repository'e göndermek için aşağıdaki butonlardan hangisine tıklamalıyız?

- [ ] pull
- [x] push
- [ ] clone
- [ ] checkout to...





## KAYNAKÇA

- https://medium.com/fedeveloper/git-bash-ile-komut-komut-versiyonlama-a354efd3063f















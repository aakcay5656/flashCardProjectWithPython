
# flashCardProjectWithPython
This application creates a Flashcard application simulating a language learning experience. It provides an interactive interface for users to learn the English equivalents of French words. In terms of functionality, it follows these steps:

## Data Reading:

Firstly, the program attempts to read a CSV file containing the list of words to be learned. If this file is not found, it uses an original CSV file containing French words.

## Displaying and Translating Cards:

It shows a card to the user with the French word on the front and its English translation on the back.
The card is initially shown in French, and after a certain duration (here, 3 seconds), it automatically flips to its English translation.

## Known and Unknown Words:

The user can click on "Known" or "Unknown" buttons beneath each card to indicate whether the word has been learned or not.
If the "Unknown" button is clicked, the word is not removed from the listening list and the next card is shown.
If the "Known" button is clicked, the word is removed from the list, and the next card is displayed.

## Data Update:

After the user marks each card, the updated word list is saved to a CSV file. This file allows the program to remember the previous learning state when closed and reopened.
This way, the user can mark words they have learned or struggled with, and the application continues to interactively introduce new words, enhancing the language learning experience.

--------------------------------------

# flashCardProjectWithPython
bir dil öğrenme uygulamasını simüle eden bir Flashcard (Hatırlatıcı Kart) uygulamasını oluşturur. Kullanıcıya, Fransızca kelimelerin İngilizce karşılıklarını öğrenmeye yönelik etkileşimli bir arayüz sunar. İşlevsellik açısından şu adımları izler:

## Veri Okuma:

İlk olarak, program mevcut öğrenilmesi gereken kelimelerin bir listesini içeren bir CSV dosyasını okumaya çalışır. Eğer bu dosya bulunamazsa, orijinal Fransızca kelimelerin olduğu bir CSV dosyasını kullanır.

## Kart Gösterme ve Çevirme:

Kullanıcıya bir kart gösterir ve kartın ön yüzünde Fransızca kelime, arkasında ise İngilizce çevirisi bulunur.
Kart, başlangıçta Fransızca olarak gösterilir ve belirli bir süre sonra (burada 3 saniye) İngilizce çevirisine otomatik olarak döner.

## Bilinen ve Bilinmeyen Kelimeler:

Kullanıcı, her bir kartın altında bulunan "Bilindi" ve "Bilinmedi" butonlarına tıklayarak, kelimenin öğrenildiğini veya öğrenilmediğini işaretleyebilir.
"Bilinmedi" butonuna tıklanması durumunda, kelime listenin içinden kaldırılmaz ve bir sonraki kart gösterilir.
"Bilindi" butonuna tıklanması durumunda, kelime listenin içinden kaldırılır ve bir sonraki kart gösterilir.

## Veri Güncelleme:

Kullanıcının her bir kart üzerindeki işaretlemeleri sonrasında, güncellenmiş kelime listesi bir CSV dosyasına kaydedilir. Bu dosya, programın kapatılıp açıldığında önceki öğrenme durumunu hatırlamasını sağlar.
Bu şekilde, kullanıcı öğrendiği veya öğrenemediği kelimeleri işaretleyebilir ve uygulama, her seferinde yeni bir kelime sunarak dil öğrenme sürecine interaktif bir şekilde devam etmesine olanak tanır.

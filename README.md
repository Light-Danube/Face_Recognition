# Face Recognition v1.8x
The most recent release of the app:
- aspect ratio issue of the thumbnails in the xlsx-reports is solved now;
- optimization (in fact – consolidation) of the face encodings data files is now available;

Найсвіжіший випуск, вер. 1.8x:
- виправлено проблему з порушення пропорцій ескізів в xlsx-звітах;
- додано можливість оптимізації (шляхом консолідації) файлів даних кодувань обличь.

# Face Recognition v1.7
- now it's in Ukrainian and English;
- memory leaks removed (at least ones I've recognized);
- multithread approach implemented for the most "heavy" mathematics;
- slow disk IO operations are minimized;
- some other basic optimization being done (now it works up to 3 times faster than v.1.5)

- тепер українською та англійською мовою;
- "витоки" пам’яті усунене (як мінімум ті, що я виявив);
- застосовано багатопотоковий підхід для найбільш важких математичних обчислень;
- мінімізовано повільні дискові операції;
- проведено іншу базову оптимізацію (тепер працює  у 3 рази швидше, ніж вер.1.5)

# Face Recognition v1.6
Skipped / Пропущено.

# Face Recognition v1.5
I've done a good way to make an app that scans millions of pictures and then finding out wanted individuals among them. And it really works fast and accurate due to face_recognition and dlib libraries. Sure, the app could be simpler but I've needed to fill it with good usability and all reasonable safeguards. Current version of the app has Ukrainian interface only (English version is coming soon).

Я пройшов непоганий шлях задля створення додатку, що сканує мільйони фотографій та потім відшуковує серед них фото осіб, які перебувають у розшуку. І він дійсно швидко працює завдяки бібліотекам face_recognition та dlib. Безумовно, код може бути простішим, але мені було потрібно забезпечити зручність і простоту користування та передбачити усі необхідні запобіжники. Поточна версія має українську мову інтерфейсу (англійська буле незабаром).

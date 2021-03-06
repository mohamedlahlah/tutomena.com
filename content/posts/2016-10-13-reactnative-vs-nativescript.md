---
title: 'الفرق الأساسي بين NativeScript و React Native'
date: '2016-10-13'
slug: 'web-development/javascript/reactnative-vs-nativescript'
template: 'post'
categories:
  - جافاسكريبت
tags:
  - NativeScript
  - React Native
  - أندرويد
  - موبايل
thumbnail: '../thumbnails/mobile.png'
---

لا شك بأن منصتي [NativeScript](http://www.tutomena.com/web-development/javascript/native-apps-with-nativescript/) و [React Native](https://www.tutomena.com/web-development/javascript/%d9%85%d9%82%d8%af%d9%85%d8%a9-%d8%b9%d9%86-react-native/) استحوذتا بشكل كبير في الفترة الأخيرة على اهتمام مطوري الويب المهتمين بمجال **برمجة تطبيقات الهواتف الذكية**، بحيث تمكنان من برمجة تطبيقات موبايل **أصلية** بالإعتماد على لغة البرمجة جافاسكريبت، CSS و XML، وبالتالي لم يعد المطور مجبرا على تعلم لغة **جافا** من أجل برمجة تطبيقات أندرويد ولا لغة **سويفت** أو Objective-C لبرمجة تطبيقات iOS.

ورغم أن كل من NativeScript و React Native تتشاركان نفس الهدف إلا أنهما تختلفان في أمور مهمة سنذكر منها نقطتين أساسيتين :

## كتابة وتنظيم أكواد الجافاسكريبت

يعتمد React-Native في كتابة وتنظيم أكواد الجافاسكريبت على مكتبة [**React.js**](https://www.tutomena.com/web-development/javascript/react-javascript-library/)، إذن أنت مجبر على تعلم React.js إذا أردت الإنتقال لبرمجة تطبيقات الموبايل الأصلية بواسطة منصة React-Native. أسباب هذا القرار بسيطة وواضحة إذا علمنا أن كل من React.js و **React Native** يتبعان للشركة العملاقة فيسبوك.

أما NativeScript فلا يجبرك على تعلم أي مكتبة أو إطار عمل إذا أردت العمل عليه، كل ما يتطلبه الأمر هو معرفة جيدة بلغة البرمجة جافاسكريبت وستتمكن بعدها من برمجة تطبيق أصلي Native احترافي قابل للنشر على متجر Google Play أو متجر App Store إذا كان التطبيق خاص بنظام التشغيل iOS، مع العلم أن التوفر على حاسوب Mac وتنصيب بيئة العمل Xcode أمران ضروريان لبرمجة تطبيقات iOS على كلتا المنصتين.

الجديد كذلك مع **NativeScript** أنه يعطيك اختيارا ثانيا، وهو امكانية الإعتماد على إطار العمل [**Angular 2**](http://www.tutomena.com/web-development/javascript/choose-angular/) لكتابة أكواد الجافاسكريبت، ولو قمت بزيارة [الموقع الرسمي](https://www.nativescript.org/) فستلاحظ أنهم يطلبون منك أي من الخيارين تفضل للبدء في انجاز مشروعك وكلاهما كما ذكرنا مدعومان بشكل رسمي من مطوري **NativeScript**.

## الفرق الأساسي

النقطة السابقة تشكل فرقا مهما بين NativeScript و React-Native، ولكن الفرق الأساسي والجوهري بينهما يكمن في الفلسفة والمقاربة التي يتبناها كل منهما. فمنصة NativeScript تمكن من إضافة واجهات رسومية User Interfaces لكل من أندرويد و iOS انطلاقا من شيفرة برمجية واحدة أي أنك لن تضطر لإنشاء واجهة **UI Components** لكل تطبيق على حدة، وهذه المقاربة نفسها تتبعها منصة كوردوفا لبرمجة تطبيقات المحمول الهجينة Hybrid والهدف الأول منها ربح الوقت.

في الجهة الأخرى، يتبع React-Native فلسفة مغايرة تماما شعارها _تعلم مرة واحدة واكتب في كل مكان_ (learn once write everywhere)، تعلم إطار العمل React.js وكيفية التعامل مع **React Native** مرة واحدة وبعدها ستكون قادرا على برمجة تطبيقات محمول أصلية لكل المنصات المدعومة (Android و iOS) ولكن لكل منصة ستقوم ببرمجة واجهات المستخدم **User Interfaces** الخاصة بها، تماما كما كنت تفعل مع **جافا** و **سويفت** ولكن الأمر الإيجابي هذه المرة أنك ستفعلها باعتماد نفس التقنيات واللغات وهذا مثير للإهتمام كذلك.

### خاتمة

بداية مطوري الويب مع تطبيقات الهواتف الذكية كانت مع كوردوفا (أو PhoneGap) وقد كانت الخطوة الأولى التي فتحت الباب لظهور هذا النوع الجديد من التقنيات لتمكيننا، نحن مطورو الويب، من إنجاز **تطبيقات موبايل أصلية** **Native** تتمتع بقدر كبير جدا من الكفاءة والأداء. عدد لا يستهان به من [التطبيقات المعروفة](http://www.tutomena.com/web-development/javascript/react-native-showcases/) بدأت بالإعتماد على هذه الأدوات الجديدة لتحسين سير عملها Workflow والإستفادة من والوقت والأموال التي تدخرها باستخدامها في نواحي أخرى مهمة.

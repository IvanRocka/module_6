# module_6
Project_6.Recommendational_Challenge.EDA,Feature_Engineering and LightFM model.TODO:cold start and prototype system
* Целью проекта, лично для меня, был опыт разработки и проектирования рекомендательной системы. Очередная тренировка
в разведывательном анализе и генерированию фич из предоставленных данных.
* Кратко о данных: оценки пользователей с обзорами на товары.
* Этапы работы:
	-Знакомство с данными
	-EDA
	-Feature_Engineering
	-Подготовка модели LightFM
	-Тестирование модели, оценка эффективности
	-Использование nmslib для построения рекомендательной системы
	-Тестирование рекомендательной системы
	-Итоги
	-TODO
*Никнейм на Kaggle: Ivan Baukin
* В качестве метрики при оценке эффективности модели использовалась roc_auc

*TODO:
-Не получилось справиться с библиотекой streamlit и соответсвенно с Heroku, оставляю на доработку, потому что и так уже просрочил
дату сдачи проекта.
-Не понял как составлять и использовать матрицу item-features.
-Не хватило времени на разработку алгоритма cold start для новых пользователей
////////////////*******///////////////////
The goal of the project, for me personally, was the experience of developing and designing a recommendation system. Another training
 in EDA  and Feature_Engineering.
* Data Summary: User ratings with product reviews.
* Work stages:
 - Initial data view
 - EDA
 - Feature_Engineering
 - Preparing the LightFM model
 - Testing the model, evaluating the effectiveness of the model
 - Using nmslib to build a recommendation system
 - Testing the recommendation system
 - Results
 - TODO
* Nickname on Kaggle: Ivan Baukin
* ROC_AUC was used as a metric for evaluating the effectiveness of the model

*TODO:
-I could not handle (cope) with the streamlit library and, accordingly, with Heroku, I leave it for revision, because I have already expired
the project delivery date.
-I didn't understand how to create and use the item-features matrix.
-I didn't have enough time to develop the cold start algorithm for new users
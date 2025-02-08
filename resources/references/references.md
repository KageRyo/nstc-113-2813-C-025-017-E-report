# 文獻回顧(專題)
1. 在過去十年內，人工智慧的研究從長期被忽視的陰霾中走了出來，被人們看見了希望且掀起了新一波風潮(Cowls, 2021)
    ```
    Cowls, J. (2021). ‘AI for Social Good’: Whose Good and Who’s Good? Introduction to the Special Issue on Artificial Intelligence for Social Good. Philosophy & Technology, 34(Suppl 1), 1–5. 
    ```

2. 在其各項發展中，機器學習在水質評估上已被證明是有效的，並成為了水資源管理的一種分析策略(Zhou et al., 2023)。
    ```
    Zhou, Y., Wang, X., Li, W., Zhou, S., & Jiang, L. (2023). Water Quality Evaluation and Pollution Source Apportionment of Surface Water in a Major City in Southeast China Using Multi-Statistical Analyses and Machine Learning Models. International Journal of Environmental Research and Public Health, 20(1). 
    ```

3. Im et al.(2022)應用了各種技術構建學習模型，可以提供即時準確水質資訊，並通過早期診斷水質異常以改善公共健康。
    ```
    Im, Y., Song, G., Lee, J., & Cho, M. (2022). Deep Learning Methods for Predicting Tap-Water Quality Time Series in South Korea. Water (20734441), 14(22), 3766. 
    ```

4. 隨著人工智慧發展，各種機器學習模型也如雨後春筍般出現，如Imran et al.(2022)開發一種基於多元多項式迴歸（MPR）的機器學習模型，比較線性迴歸及支援向量機模型後發現，MPR在性能評估指標包含R²（R-squared）和RMSE（Root-Mean-Square Error）上皆優於另外兩個模型。Imran et al.(2022)所提出的MPR公式如(1)所示，其中y ̂是輸出變數，w_0是截距，w_1、w_2…w_s為多項式迴歸係數，x為輸入變數，表示具有n個輸入變數和階數（s > 1）的MPR系統。![pic1](<../image/Imran et al.(2022).png>)(1)
    ```
    Imran, H., Al-Abdaly, N. M., Shamsa, M. H., Shatnawi, A., Ibrahim, M., & Ostrowski, K. A. (2022). Development of prediction model to predict the compressive strength of eco-friendly concrete using multivariate polynomial regression combined with stepwise method. Materials, 15(1), 317.
    ```

5. 其他研究成果如Narayan & Daniel.(2022)使用MPR模型驗證其預測結果
    ```
    Narayan, V., & Daniel, A. K. (2022). Energy Efficient Protocol for Lifetime Prediction of Wireless Sensor Network using Multivariate Polynomial Regression Model.
    ```

6. 如圖2所示，Canamero et al.(2023)以MPR建立了一個六元多項式迴歸模型，結果顯示其訓練集的MAPE（Mean Absolute Percentage Error）為1.873%，MAE（Mean Absolute Error）為0.017，RMSE為0.024，R²為0.848；測試集的MAPE為1.503%，MAE為0.014，RMSE為0.017，R²為0.9072。![pic2](<../image/Canamero et al.(2023).png>)(2)
    ```
    Canamero, F. J., Doraisingam, A. R., & Alvarez-Leal, M. (2023). Mixing Performance Prediction of Detergent Mixing Process Based on the Discrete Element Method and Machine Learning. Applied Sciences, 13(10), 6094.
    ```

7. 如圖3所示，Zeini et al.(2023) 以MPR分析245個實驗資料，並使用5折交叉方法驗證MPR的準確性和泛化能力皆優於線性迴歸（LR）與隨機森林（RF）模型，該MPR模型在訓練集和測試集上的R²值分別為0.994和0.983，而RMSE為13.01和15.655。![pic3](<../image/Zeini et al.(2023).png>)(3)
    ```
    Zeini, H. A., Lwti, N. K., Imran, H., Henedy, S. N., Bernardo, L. F. A., & Al-Khafaji, Z. (2023). Prediction of the Bearing Capacity of Composite Grounds Made of Geogrid-Reinforced Sand over Encased Stone Columns Floating in Soft Soil Using a White-Box Machine Learning Model. Applied Sciences, 13(8), 5131.
    ```

8. 此外，多元多項式迴歸（MPR）具有可塑性，能夠依照不同需求而構建出符合其需求的MPR模型。Huang et al.(2019)基於MPR原理對30個開源專案進行分析，並和另外6種模型分別以AAE（Absolute Average Error）和平均相對誤差ARE（Average Relative Error）進行比較，在ant項目上的勝率為4/5、jedit為4/4、synapse及xalan為3/3、xerces為2/2、prop為4/6（AAE）和3/6（ARE），足以證明MPR的性能良好且具有競爭力。
    ```
    Huang, Q., Ni, C., Chen, X., Gu, Q., & Cao, K. (2019). Multi-project Regression based Approach for Software Defect Number Prediction. In SEKE (pp. 425-546).
    ```

9. Wang et al.(2021)以IoT方式蒐集水質資料，並使用MPR和GRNN（General Regression Neural Networ）模型進行比較，結果對於8次方的MPR模型，於NO3-N、BOD5、PO4和NH3-N項目的決定係數R²分別為0.89、0.78、0.87和0.81，在驗證後確認預測誤差小於0.2 mg/L，亦證明MPR對水質資料分析上具有效性。
    ```
    Wang, Y., Ho, I. W. H., Chen, Y., Wang, Y., & Lin, Y. (2021). Real-time water quality monitoring and estimation in AIoT for freshwater biodiversity conservation. IEEE Internet of Things Journal.
    ```

# 材料與方法(專題)
10. 支援各式開源函式庫使得Python成為資料分析的熱門選擇(McKinney, 2022)
    ```
    McKinney W. (2022). Python for Data Analysis: Vol. Third edition. O’Reilly Media.
    ```
    
11. 且能夠有效處理即時、大型和非結構化資料(Harnowo et al., 2022)
    ```
    Harnowo, A. (2022). Blending a MOOC course into a Business School’s Course to Introduce Python for Data Analytics. Business Education Innovation Journal, 14(2), 31–35.
    ```

12. NumPy是Python程式語言中支援科學和數值計算的函式庫，也相容於Pandas、Matplotlib和Scikit-learn等工具(Harris et al., 2020)。
    ```
    Harris, C. R., Millman, K. J., Van Der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., ... & Oliphant, T. E. (2020). Array programming with NumPy. Nature, 585(7825), 357-362.
    ```

13. NumPy作為資料處理的主要工具是因為它提供了科學計算所需的基本資料結構(Nishino et al., 2017)
    ```
    Nishino, R. O. Y. U. D., & Loomis, S. H. C. (2017). Cupy: A numpy-compatible library for nvidia gpu calculations. 31st confernce on neural information processing systems, 151(7).
    ```

14. 同時NumPy也提供豐富的數學運算、資料讀寫、線性代數、傅立葉變換和隨機數生成等功能函式(McKinney, 2012)
    ```
    McKinney, W. (2012). Python for data analysis: Data wrangling with Pandas, NumPy, and IPython. " O'Reilly Media, Inc.".
    ```

15. Pandas建立於NumPy的基礎之上，是一種用於格式化資料分析的開源Python函式庫，它能夠處理類似電子試算表格式的輸入資料，可以快速地進行資料載入、操作、對齊和合併等功能(Chen, 2017)
    ```
    Chen, D. Y. (2017). Pandas for everyone: Python data analysis. Addison-Wesley Professional.
    ```

16. 採用了Scikit-learn作為機器學習框架，以建構研究所需的多元多項式迴歸（MPR）模型(Aurélien, 2022)
    ```
    Aurélien Géron. (2022). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 3rd Edition. O’Reilly Media, Inc.
    ```

17. 支援Python程式的機器學習框架之中，Scikit-learn提供多樣的演算法，其特色包括具有良好的應用程式介面（Application Programming Interface, API）、詳細文檔說明及技術支援(Pedregosa et al., 2011)
    ```
    Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., ... & Duchesnay, E. (2011). Scikit-learn: Machine Learn-ing in Python, Journal of Machine Learning Re-search, 12.
    ```

18. Matplotlib是一個多功能的Python繪圖函式庫，具有產生各種類型和格式圖表的功能，包括折線圖、散布圖、熱圖、直方圖、圓餅圖和立體圖形，同時也支援動畫和互動顯示(Hunt, 2023)
    ```
    Hunt, J. (2023). Introduction to Matplotlib. In Advanced Guide to Python 3 Programming, Cham: Springer International Publishing, 121-128.
    ```

19. FastAPI是一個新興但可靠的API框架(Bill, 2024)
    ```
    Bill Lubanovic. (2024). FastAPI. O’Reilly Media.
    ```

20. Bansal & Ouda.(2022)將機器學習模型與使用FastAPI服務的前端整合，結果相較使用如Flask等其他API框架的效能提高了45%
    ```
    Bansal, P., & Ouda, A. (2022, July). Study on integration of fastapi and machine learning for continuous authentication of behavioral biometrics. In 2022 International Symposium on Networks, Computers and Communications (ISNCC) (pp. 1-6). IEEE.
    ```

21. React Native框架。此框架由Meta公司基於React框架與JavaScript語言設計開發，重點在於能夠開發跨操作系統運行的行動裝置應用程式，作業系統支援包括Android及iOS（Native, 2020）
    ```
    Native, R. (2020). React native. línea]. Disponible en: https://reactnative. dev/.[Último acceso: 2 de noviembre 2019].
    ```

22. 考慮到多元多項式迴歸（MPR）模型的訓練需要連續分佈的資料，實作上可選擇以填補的方式保持水質資料的完整性，方式包括使用常見值填補、平均值填補、模型預測填補、相似案例填補或使用特殊標記表示遺失值(Kotsiantis et al., 2006)
    ```
    Kotsiantis, S. B., Kanellopoulos, D., & Pintelas, P. E. (2006). Data preprocessing for supervised leaning. International journal of computer science, 1(2), 111-117.
    ```

23. Burlig et al.(2020)使用修剪法（Trimming）排除機器學習模型資料集中的異常極端值，於整體水質資料集中，刪除中位數1%及99%之極端值，提升模型的性能
    ```
    Burlig, F., Knittel, C., Rapson, D., Reguant, M., & Wolfram, C. (2020). Machine learning from schools about energy efficiency. Journal of the Association of Environmental and Resource Economists, 7(6), 1181-1217.
    ```

24. Ajona & Vasanthi.(2022)使用兩個迴歸模型建立因變數和自變數間的關係，該研究將整個資料集被分為訓練集和測試集，分别占總體資料的80%和20%，訓練集用於建立迴歸方程，測試集用於驗證模型
    ```
    Ajona, M., Vasanthi, P., & Vijayan, D. S. (2022). Application of multiple linear and polynomial regression in the sustainable biodegradation process of crude oil. Sustainable Energy Technologies and Assessments, 54, 102797.
    ```

25. 以公式(2)為例，其表示一個二階多元多項式(Sinha, 2013)y=β_0+β_1 x_1+β_2 x_2+β_11 x_1^2+β_22 x_2^2+β_12 x_1 x_2(2)
    ```
    Sinha, P. (2013). Multivariate polynomial regression in data mining: methodology, problems and solutions. Int. J. Sci. Eng. Res, 4(12), 962-965.
    ```

26. 最小平方法所欲解決的基本問題在於當給定n個觀察值時，找到擬合直線的最佳解，如公式(3)所示(Miller, 2006)。y=a_1 f_1 (x)+⋯+c_k f_k (x)	(3)
    ```
    
    ```

27. SGD是一種迭代方法，其更新權重的公式如(4)所示，具有應用在大量資料下，仍可維持高效率計算之特性(Murphy, 2022)	w=w-η∇E_i (w)	(4)
    ```
    Miller, S. J. (2006). The method of least squares. Mathematics Department Brown University, 8, 1-7.
    ```

28. 水體品質指標（Water Quality Index, 〖WQI〗_5），WQI能夠將大量水質資料轉換如等級一樣的數值，比起各種參數的一長算數值更容易理解與運用，使人們更容易理解水質資料呈現的結果（Jawed et al., 2010）	〖WQI〗_5=(∑_(i=1)^5▒〖(W_i Q_i)〗^1.5 )/10	(8)
    ```
    Abdul Hameed M Jawad, A., Bahram K, M., & Abass J, K. (2010). Evaluating raw and treated water quality of Tigris River within Baghdad by index analysis. journal of water resource and protection, 2010.
    ```

# 碩推研究計畫
1. 人工智慧的未來具有非常大的發展潛力[1]
    ```
    Dwivedi, Y. K., Hughes, L., Ismagilova, E., Aarts, G., Coombs, C., Crick, T., ... & Williams, M. D. (2021). Artificial Intelligence (AI): Multidisciplinary perspectives on emerging challenges, opportunities, and agenda for research, practice and policy. International Journal of Information Management, 57, 101994.
    ```

2. 近十年來，人工智慧從理論發展到實際應用，生成式 AI 等工具也被廣泛運用於日常問題的解決[2]
    ```
    Shao, Z., Zhao, R., Yuan, S., Ding, M., & Wang, Y. (2022). Tracing the evolution of AI in the past decade and forecasting the emerging trends. Expert Systems with Applications, 209, 118221.
    ```

3. 人工智慧未來將成為人類不可或缺的夥伴[3]
    ```
    Aggarwal, K., Mijwil, M. M., Al-Mistarehi, A. H., Alomari, S., Gök, M., Alaabdin, A. M. Z., & Abdulrhman, S. H. (2022). Has the future started? The current growth of artificial intelligence, machine learning, and deep learning. Iraqi Journal for Computer Science and Mathematics, 3(1), 115-123.
    ```

4. 遺失值（Missing Data）處理可以選擇直接刪除或進行填補兩種作法。如水值資料分析模型的訓練需要連續分佈的資料，實作上可選擇以填補的方式保持水質資料的完整性，方式包括使用常見值填補、平均值填補、模型預測填補、相似案例填補或使用特殊標記表示遺失值[4]
    ```
    Kotsiantis, S. B., Kanellopoulos, D., & Pintelas, P. E. (2006). Data preprocessing for supervised learning. International Journal of Computer Science, 1(2), 111-117.
    ```

5. 可以使用修剪法（Trimming）排除機器學習模型資料集中的極端值[5]
    ```
    Burlig, F., Knittel, C., Rapson, D., Reguant, M., & Wolfram, C. (2020). Machine learning from schools about energy efficiency. Journal of the Association of Environmental and Resource Economists, 7(6), 1181-1217.
    ```
    
6. 正規化（Normalization）將數值資料縮放到[0, 1]的範圍，可能會導致異常值造成的資料遺失，因此使用標準化（Standardization）更佳。標準化將輸入參數的均值（μ=0）和方差（σ=1）進行調整，使資料更符合常態分佈[6]
    ```
    Sharma, P., & Singh, J. (2018, September). Machine learning based effort estimation using standardization. In 2018 International Conference on Computing, Power and Communication Technologies (GUCON) (pp. 716-720).  Greater Noida, NCR New Delhi, India.
    ```

7. 實作上能將整個資料集被分為訓練集和測試集，分别占整體80%和20%[7]
    ```
    Ajona, M., Vasanthi, P., & Vijayan, D. S. (2022). Application of multiple linear and polynomial regression in the sustainable biodegradation process of crude oil. Sustainable Energy Technologies and Assessments, 54, 102797.
    ```

8. 特徵工程（Feature Engineering）在機器學習過程中至關重要，能將資料轉換成模型可以理解的特徵，或將變數處理成特徵[8]
    ```
    Verdonck, T., Baesens, B., Óskarsdóttir, M., & vanden Broucke, S. (2024). Special issue on feature engineering editorial. Machine Learning, 113(7), 3917-3928.
    ```

9. MPR相較於傳統的線性迴歸（Linear Regression, LR）模型，在水質資料分析上表現更優越，且亦有研究指出MPR較支援向量機（Support Vector Machine, SVM）[9]
    ```
    Imran, H., Al-Abdaly, N. M., Shamsa, M. H., Shatnawi, A., Ibrahim, M., & Ostrowski, K. A. (2022). Development of prediction model to predict the compressive strength of eco-friendly concrete using multivariate polynomial regression combined with stepwise method. Materials, 15(1), 317.
    ```

10. 及隨機森林樹（Random Forest, RF）[10]更佳
    ```
    Zeini, H. A., Lwti, N. K., Imran, H., Henedy, S. N., Bernardo, L. F. A., & Al-Khafaji, Z. (2023). Prediction of the Bearing Capacity of Composite Grounds Made of Geogrid-Reinforced Sand over Encased Stone Columns Floating in Soft Soil Using a White-Box Machine Learning Model. Applied Sciences, 13(8), 5131.
    ```

11. XGBoost在資料科學領域中被廣泛使用，也在Kaggle許多機器學習及競賽中取得最佳結果，其特點為有非常強的擴展性（Scalibility）與性能，可以使用相對其他模型更少的系統資源，擴充數十億級別的資料[11]
    ```
    Chen, T., & Guestrin, C. (2016, August). XGBoost: A scalable tree boosting system. In Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (pp. 785-794). New York, NY, United States.
    ```

12. LightGBM是一種高效能的梯度提升決策樹，在傳統Gradient Boosting Decision Tree（GBDT）演算法上加入使用Gradient-based One-Side Sampling（GOSS）和 Exclusive Feature Bunding （EFB），並顯示出LightGBM相較傳統的GBDT加快了20倍以上的速度，同時也並未降低準確性[12]
    ```
    Ke, G., Meng, Q., Finley, T., Wang, T., Chen, W., Ma, W., ... & Liu, T. Y. (2017). LightGBM: A highly efficient gradient boosting decision tree. Advances in Neural Information Processing Systems, 30.
    ```

13. 交叉驗證（Cross Validation）能夠用於超參數（Hyperparameter）調整，能夠防止過擬合的發生，並進行模型泛化的評估[13]
    ```
    Berrar, D. (2019) Cross-Validation. In: Ranganathan, S., Gribskov, M., Nakai, K. and Christian Schönbach, C., Eds., Reference Module in Life Sciences Encyclopedia of Bioinformatics and Computational Biology, Vol. 1, Elsevier, Amsterdam, 542-545.
    ```
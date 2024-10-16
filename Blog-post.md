# Unlocking Insights from Seattle’s Airbnb Market: What Drives Listing Prices?

Seattle’s vibrant culture, tech-driven economy, and picturesque surroundings make it a top destination for travelers, and Airbnb plays a huge role in accommodating visitors. With so many properties available, have you ever wondered what factors influence the price of an Airbnb listing? By diving into Seattle’s Airbnb data, we aimed to answer key questions about what drives the cost of a night’s stay.

In this blog post, I will walk you through the main findings of this analysis, which could help both hosts and travelers better understand how listing prices are shaped.

## Our Questions of Interest:

1. **What months witnessed the peak of the average listing nightly price in Seattle?**
2. **What are the top 3 listing neighbourhood groups in terms of average nightly price in Seattle?**
3. **What factors are most correlated with predicting the listing nightly price?**

---

### 1. What months witnessed the peak of the average listing nightly price in Seattle?

Seattle draws visitors year-round. However, the demand for Airbnb listings varies by season, and so do the prices. Our analysis shows that the months of **June, July**, and **August** consistently experience the highest average listing prices.

This seasonal trend is likely driven by the summer months when Seattle’s weather is at its best, attracting tourists for outdoor activities, festivals, and city explorations.

Looking deeper into the data, we see the price spike is heavily observed with listings in **Downtown** more than in any other neighborhood group.

---

### 2. What are the top 3 listing neighbourhood groups in terms of average nightly price in Seattle?

When looking at the average nightly prices across Seattle's neighborhood groups, three areas stand out:

- **Magnolia:** With an average nightly price of 178 USD, Magnolia tops the list. However, it's important to note that this neighborhood has a relatively small number of listings (only 61), which can lead to higher variability in pricing.
- **Queen Anne:** Known for its scenic views and historic architecture, Queen Anne ranks second with an average nightly price of 157 USD.
- **Downtown Seattle:** As the city's bustling commercial center, Downtown comes in third with an average nightly price of 155 USD. Its central location and proximity to attractions make it highly desirable for visitors.

While Magnolia boasts the highest prices, the smaller number of listings in this area means that prices may fluctuate more compared to the larger, more diverse markets of Queen Anne and Downtown.

---

### 3. What factors are most correlated with predicting the listing nightly price?

Understanding which factors contribute the most to listing prices is crucial for hosts and travelers alike. Our analysis of Airbnb listings in Seattle reveals that the following factors are most correlated with predicting the nightly price:

- **Accommodation capacity:** Larger listings with more rooms and beds tend to command higher prices.
- **Amenities:** Features such as air conditioning, washer/dryer, and luxury amenities like hot tubs or indoor fireplaces increase the value of a listing.
- **Location:** As previously discussed, being located in highly sought-after neighborhoods significantly impacts the price.

By using Lasso regression to analyze the dataset, we identified the factors that have the greatest impact on listing prices, offering a roadmap for hosts aiming to optimize their listings.

---

## Conclusion

Seattle's Airbnb market follows clear trends in pricing, influenced by seasonal demand, neighborhood location, and listing features. For travelers, the insights into when and where to book can result in savings. For hosts, understanding the factors that drive prices can help maximize their income potential. Whether you're planning your next trip or listing your property, knowing these patterns ensures you make the most informed decisions.

If you're interested in diving deeper into the analysis, you can clone and explore the data and detailed analysis in my GitHub repository.

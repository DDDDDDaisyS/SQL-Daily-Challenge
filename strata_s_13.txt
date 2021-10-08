SELECT from_type, ROUND(AVG(review_score), 2) AS avg_score
FROM airbnb_reviews
GROUP BY from_type
ORDER BY avg_score DESC
LIMIT 1;

SELECT
  Subject,
  Country,
  Value,
  Frequency
FROM
  `UAS_inflation.inflation`
WHERE
  Value < 59.84822
ORDER BY
  Frequency;

  # or go to link https://console.cloud.google.com/bigquery?sq=706905179759:a868d93f08f04b989b4789aa074add50
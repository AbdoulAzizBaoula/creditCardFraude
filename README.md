# PROJET ANALYSE DES FRAUDES DE CARTES DE CREDIT

### Cet ensemble de données comprend les transactions par carte de crédit dans l'ouest des États-Unis. Il comprend des informations sur chaque transaction, y compris les détails du client, le commerçant et la catégorie d'achat, et si la transaction était ou non une fraude...

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AbdoulAzizBaoula/creditCardFraude/main?labpath=index.ipynb)


## Dictionnaire de données
#### transdatetrans_time	: DateHeure de la transaction
#### merchant	: Nom du commerçant
#### category	: Catégorie de commerçant
#### amt	: Montant de la transaction
#### city	: Titulaire de la carte de crédit de la ville de
#### state	: État du titulaire de la carte de crédit
#### lat	: Latitude Lieu d'achat
#### long	: Longitude Lieu d'achat
#### city_pop	: Population de la ville du titulaire de la carte de crédit
#### job	: Emploi de titulaire de carte de crédit
#### dob	: Date de naissance du titulaire de la carte de crédit
#### trans_num	: Numéro de transaction
#### merch_lat	: Latitude Emplacement du marchand
#### merch_long	: Longitude de l'emplacement du marchand
#### is_fraud	: Si la transaction est une fraude (1) ou non (0)
 
## :file_folder: Aperçu du dataset analysé


|    | trans_date_trans_time   | merchant                    | category      |    amt | city                     | state   |     lat |     long |   city_pop | job                               | dob        | trans_num                        |   merch_lat |   merch_long |   is_fraud |
|---:|:------------------------|:----------------------------|:--------------|-------:|:-------------------------|:--------|--------:|---------:|-----------:|:----------------------------------|:-----------|:---------------------------------|------------:|-------------:|-----------:|
|  0 | 2019-01-01 00:00:44     | "Heller, Gutmann and Zieme" | grocery_pos   | 107.23 | Orient                   | WA      | 48.8878 | -118.21  |        149 | Special educational needs teacher | 1978-06-21 | 1f76529f8574734946361c461b024d99 |     49.159  |     -118.186 |          0 |
|  1 | 2019-01-01 00:00:51     | Lind-Buckridge              | entertainment | 220.11 | Malad City               | ID      | 42.1808 | -112.262 |       4154 | Nature conservation officer       | 1962-01-19 | a1a22d70485983eac12b5b88dad1cf95 |     43.1507 |     -112.154 |          0 |
|  2 | 2019-01-01 00:07:27     | Kiehn Inc                   | grocery_pos   |  96.29 | Grenada                  | CA      | 41.6125 | -122.526 |        589 | Systems analyst                   | 1945-12-21 | 413636e759663f264aae1819a4d4f231 |     41.6575 |     -122.23  |          0 |
|  3 | 2019-01-01 00:09:03     | Beier-Hyatt                 | shopping_pos  |   7.77 | High Rolls Mountain Park | NM      | 32.9396 | -105.819 |        899 | Naval architect                   | 1967-08-30 | 8a6293af5ed278dea14448ded2685fea |     32.8633 |     -106.52  |          0 |
|  4 | 2019-01-01 00:21:32     | Bruen-Yost                  | misc_pos      |   6.85 | Freedom                  | WY      | 43.0172 | -111.029 |        471 | "Education officer, museum"       | 1967-08-02 | f3c43d336e92a44fc2fb67058d5949e3 |     43.7537 |     -111.455 |          0 |

 

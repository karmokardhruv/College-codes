# College-codes
All the codes that I could find from my college course

for i in 51 52 53 54 55 56 57 59 20 21 22 23 24 25 31 32 41 42 43 60 61 213 214 215 66 63 16 29 30
do
echo "========================= vg 00 of 10.0.20.$i ====================="
ssh -q 10.0.20.$i bdf | grep -i "vg00"
echo "========================= vg 00 ====================="
done
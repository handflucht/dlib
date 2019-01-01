# dlib
dlib with BLAS and models, ready to run.

# Usage
`
docker run -it --rm -e DISPLAY=$DISPLAY handflucht/dlib python3 ./face_recognition.py shape_predictor_5_face_landmarks.dat dlib_face_recognition_res
net_model_v1.dat ../examples/faces
`
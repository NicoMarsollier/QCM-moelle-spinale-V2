# QCM-moelle-spinale
<!DOCTYPE html>
<html lang="fr">
<!-- [Previous head section and styles remain the same] -->
<style>
    /* Adding styles for the correction section */
    .correction {
      margin-top: 24px;
      padding: 16px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      display: none;
    }

    .correction h2 {
      color: #2c3e50;
      margin-bottom: 16px;
      font-size: 1.2rem;
    }

    .correction-item {
      margin-bottom: 16px;
      padding: 12px;
      border-radius: 8px;
      background-color: #f8f9fa;
    }

    .correction-item.correct {
      border-left: 4px solid #4CAF50;
    }

    .correction-item.incorrect {
      border-left: 4px solid #ff4444;
    }

    .show-correction-btn {
      background-color: #2196F3;
      color: white;
      width: 100%;
      padding: 16px;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      margin-top: 12px;
      transition: background-color 0.2s;
    }

    .show-correction-btn:hover {
      background-color: #1976D2;
    }
</style>

<body>
      <label>1. Quel est le rôle principal de la moelle épinière ?</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q1" value="b">
          Permettre la communication entre le cerveau et le corps
        </label>
        <label class="answer-option">
          <input type="radio" name="q1" value="a">
          Réguler la respiration
        </label>
        <label class="answer-option">
          <input type="radio" name="q1" value="c">
          Protéger les organes internes
        </label>
        <label class="answer-option">
          <input type="radio" name="q1" value="d">
          Produire du liquide céphalo-rachidien
        </label>
      </div>
    </div>

    <div class="question">
      <label>2. La moelle épinière commence au niveau de :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q2" value="b">
          Le foramen magnum
        </label>
        <label class="answer-option">
          <input type="radio" name="q2" value="a">
          L'occiput
        </label>
        <label class="answer-option">
          <input type="radio" name="q2" value="c">
          La vertèbre C1
        </label>
        <label class="answer-option">
          <input type="radio" name="q2" value="d">
          La vertèbre T12
        </label>
      </div>
    </div>

    <div class="question">
      <label>3. La moelle épinière se termine au niveau des vertèbres :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q3" value="b">
          L1-L2
        </label>
        <label class="answer-option">
          <input type="radio" name="q3" value="a">
          C1
        </label>
        <label class="answer-option">
          <input type="radio" name="q3" value="c">
          L5
        </label>
        <label class="answer-option">
          <input type="radio" name="q3" value="d">
          S1-S2
        </label>
      </div>
    </div>

    <div class="question">
      <label>4. Le cône médullaire est situé au niveau des vertèbres :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q4" value="a">
          L1-L2
        </label>
        <label class="answer-option">
          <input type="radio" name="q4" value="b">
          C7
        </label>
        <label class="answer-option">
          <input type="radio" name="q4" value="c">
          T12
        </label>
        <label class="answer-option">
          <input type="radio" name="q4" value="d">
          S1-S2
        </label>
      </div>
    </div>

    <div class="question">
      <label>5. Quelle structure est responsable de la protection de la moelle épinière ?</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q5" value="b">
          Les méninges
        </label>
        <label class="answer-option">
          <input type="radio" name="q5" value="a">
          Les vertèbres
        </label>
        <label class="answer-option">
          <input type="radio" name="q5" value="c">
          Le disque intervertébral
        </label>
        <label class="answer-option">
          <input type="radio" name="q5" value="d">
          Le ligament longitudinal postérieur
        </label>
      </div>
    </div>

    <div class="question">
      <label>6. Le filum terminale est une extension de :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q6" value="b">
          La pie-mère
        </label>
        <label class="answer-option">
          <input type="radio" name="q6" value="a">
          La dure-mère
        </label>
        <label class="answer-option">
          <input type="radio" name="q6" value="c">
          La moelle épinière
        </label>
        <label class="answer-option">
          <input type="radio" name="q6" value="d">
          La queue de cheval
        </label>
      </div>
    </div>

    <div class="question">
      <label>7. Les cornes dorsales de la moelle épinière sont responsables de :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q7" value="b">
          La réception des informations sensorielles
        </label>
        <label class="answer-option">
          <input type="radio" name="q7" value="a">
          L'émission des informations motrices
        </label>
        <label class="answer-option">
          <input type="radio" name="q7" value="c">
          La circulation du liquide céphalo-rachidien
        </label>
        <label class="answer-option">
          <input type="radio" name="q7" value="d">
          La régulation de la température corporelle
        </label>
      </div>
    </div>

    <div class="question">
      <label>8. Quelle est la principale fonction de la substance blanche de la moelle épinière ?</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q8" value="c">
          Transmettre les informations nerveuses
        </label>
        <label class="answer-option">
          <input type="radio" name="q8" value="a">
          Réceptionner les informations sensorielles
        </label>
        <label class="answer-option">
          <input type="radio" name="q8" value="b">
          Produire des neurohormones
        </label>
        <label class="answer-option">
          <input type="radio" name="q8" value="d">
          Nourrir les cellules nerveuses
        </label>
      </div>
    </div>

    <div class="question">
      <label>9. Les artères radiculaires pénètrent dans la moelle épinière par :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q9" value="b">
          Les foramens intervertébraux
        </label>
        <label class="answer-option">
          <input type="radio" name="q9" value="a">
          Le foramen magnum
        </label>
        <label class="answer-option">
          <input type="radio" name="q9" value="c">
          Les pédicules vertébraux
        </label>
        <label class="answer-option">
          <input type="radio" name="q9" value="d">
          La canalisation veineuse
        </label>
      </div>
    </div>

    <div class="question">
      <label>10. Le plexus brachial innervé :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q10" value="c">
          Les membres supérieurs
        </label>
        <label class="answer-option">
          <input type="radio" name="q10" value="a">
          Les membres inférieurs
        </label>
        <label class="answer-option">
          <input type="radio" name="q10" value="b">
          Le tronc
        </label>
        <label class="answer-option">
          <input type="radio" name="q10" value="d">
          La tête
        </label>
      </div>
    </div>

    <div class="question">
      <label>11. Le plexus lombaire est formé par les racines des segments :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q11" value="c">
          L1-L4
        </label>
        <label class="answer-option">
          <input type="radio" name="q11" value="a">
          C1-C4
        </label>
        <label class="answer-option">
          <input type="radio" name="q11" value="b">
          T1-T12
        </label>
        <label class="answer-option">
          <input type="radio" name="q11" value="d">
          S1-S4
        </label>
      </div>
    </div>

    <div class="question">
      <label>12. Le nerf sciatique est issu du plexus :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q12" value="d">
          Sacré
        </label>
        <label class="answer-option">
          <input type="radio" name="q12" value="c">
          Lombaire
        </label>
        <label class="answer-option">
          <input type="radio" name="q12" value="b">
          Brachial
        </label>
        <label class="answer-option">
          <input type="radio" name="q12" value="a">
          Cervical
        </label>
      </div>
    </div>

    <div class="question">
      <label>13. Les artères spinales postérieures irriguent principalement :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q13" value="c">
          La partie postérieure de la moelle
        </label>
        <label class="answer-option">
          <input type="radio" name="q13" value="a">
          La substance grise
        </label>
        <label class="answer-option">
          <input type="radio" name="q13" value="b">
          La face antérieure de la moelle
        </label>
        <label class="answer-option">
          <input type="radio" name="q13" value="d">
          Les racines nerveuses
        </label>
      </div>
    </div>

    <div class="question">
      <label>14. Le ligament jaune se situe :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q14" value="b">
          Sur la face postérieure des vertèbres
        </label>
        <label class="answer-option">
          <input type="radio" name="q14" value="a">
          Sur la face antérieure des vertèbres
        </label>
        <label class="answer-option">
          <input type="radio" name="q14" value="c">
          Entre les vertèbres et la moelle épinière
        </label>
        <label class="answer-option">
          <input type="radio" name="q14" value="d">
          En dehors du canal rachidien
        </label>
      </div>
    </div>

  <div class="question">
      <label>15. Les rapports externes de la moelle épinière avec les pédicules vertébraux concernent :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q15" value="b">
          La communication avec les nerfs spinaux
        </label>
        <label class="answer-option">
          <input type="radio" name="q15" value="a">
          La fonction sensorielle
        </label>
        <label class="answer-option">
          <input type="radio" name="q15" value="c">
          Le soutien mécanique de la moelle
        </label>
        <label class="answer-option">
          <input type="radio" name="q15" value="d">
          La circulation sanguine de la moelle
        </label>
      </div>
    </div>

    <div class="question">
      <label>16. Le canal central de la moelle épinière est rempli de :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q16" value="a">
          Liquide céphalo-rachidien
        </label>
        <label class="answer-option">
          <input type="radio" name="q16" value="b">
          Sang
        </label>
        <label class="answer-option">
          <input type="radio" name="q16" value="c">
          Air
        </label>
        <label class="answer-option">
          <input type="radio" name="q16" value="d">
          Lymphe
        </label>
      </div>
    </div>

    <div class="question">
      <label>17. Les racines nerveuses sortent de la moelle épinière par :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q17" value="a">
          Les foramens de conjugaison
        </label>
        <label class="answer-option">
          <input type="radio" name="q17" value="b">
          Les pédicules
        </label>
        <label class="answer-option">
          <input type="radio" name="q17" value="c">
          Les ligaments longitudinaux
        </label>
        <label class="answer-option">
          <input type="radio" name="q17" value="d">
          Les lamelles vertébrales
        </label>
      </div>
    </div>

    <div class="question">
      <label>18. Le ligament longitudinal postérieur recouvre :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q18" value="a">
          La face antérieure des vertèbres
        </label>
        <label class="answer-option">
          <input type="radio" name="q18" value="b">
          La face postérieure des vertèbres
        </label>
        <label class="answer-option">
          <input type="radio" name="q18" value="c">
          La face latérale des vertèbres
        </label>
        <label class="answer-option">
          <input type="radio" name="q18" value="d">
          Les intervertébraux
        </label>
      </div>
    </div>

    <div class="question">
      <label>19. La moelle épinière est protégée par des membranes appelées :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q19" value="c">
          Méninges
        </label>
        <label class="answer-option">
          <input type="radio" name="q19" value="a">
          Ligaments
        </label>
        <label class="answer-option">
          <input type="radio" name="q19" value="b">
          Plexus
        </label>
        <label class="answer-option">
          <input type="radio" name="q19" value="d">
          Artères
        </label>
      </div>
    </div>

    <div class="question">
      <label>20. Le principal rôle de la substance grise dans la moelle épinière est :</label>
      <div class="answers">
        <label class="answer-option">
          <input type="radio" name="q20" value="c">
          L'émission des informations motrices et la réception sensorielle
        </label>
        <label class="answer-option">
          <input type="radio" name="q20" value="a">
          La conduction des informations sensorielles
        </label>
        <label class="answer-option">
          <input type="radio" name="q20" value="b">
          La production de liquide céphalo-rachidien
        </label>
        <label class="answer-option">
          <input type="radio" name="q20" value="d">
          La protection de la moelle contre les infections
        </label>
      </div>
    </div>

    <button type="button" class="submit-btn" onclick="evaluateQuiz()">Soumettre</button>
  </form>
  
  <div class="result" id="result"></div>
  <button type="button" class="show-correction-btn" onclick="showCorrection()" id="correctionBtn" style="display:none">
    Voir la correction
  </button>
  <div class="correction" id="correction"></div>

  <script>
    const correctAnswers = {
      q1: { value: "b", explanation: "La moelle épinière assure la communication entre le cerveau et le corps" },
      q2: { value: "b", explanation: "La moelle épinière commence au niveau du foramen magnum" },
      q3: { value: "b", explanation: "La moelle épinière se termine au niveau des vertèbres L1-L2" },
      q4: { value: "a", explanation: "Le cône médullaire est situé au niveau des vertèbres L1-L2" },
      q5: { value: "b", explanation: "Les méninges sont responsables de la protection de la moelle épinière" },
      q6: { value: "b", explanation: "Le filum terminale est une extension de la pie-mère" },
      q7: { value: "b", explanation: "Les cornes dorsales sont responsables de la réception des informations sensorielles" },
      q8: { value: "c", explanation: "La substance blanche transmet les informations nerveuses" },
      q9: { value: "b", explanation: "Les artères radiculaires pénètrent par les foramens intervertébraux" },
      q10: { value: "c", explanation: "Le plexus brachial innerve les membres supérieurs" },
      q11: { value: "c", explanation: "Le plexus lombaire est formé par les racines L1-L4" },
      q12: { value: "d", explanation: "Le nerf sciatique est issu du plexus sacré" },
      q13: { value: "c", explanation: "Les artères spinales postérieures irriguent la partie postérieure de la moelle" },
      q14: { value: "b", explanation: "Le ligament jaune se situe sur la face postérieure des vertèbres" },
      q15: { value: "b", explanation: "Les rapports externes concernent la communication avec les nerfs spinaux" },
      q16: { value: "a", explanation: "Le canal central est rempli de liquide céphalo-rachidien" },
      q17: { value: "a", explanation: "Les racines nerveuses sortent par les foramens de conjugaison" },
      q18: { value: "a", explanation: "Le ligament longitudinal postérieur recouvre la face antérieure des vertèbres" },
      q19: { value: "c", explanation: "La moelle épinière est protégée par les méninges" },
      q20: { value: "c", explanation: "La substance grise est responsable de l'émission motrice et de la réception sensorielle" }
    };

    function evaluateQuiz() {
      let score = 0;
      const results = [];

      for (let i = 1; i <= 20; i++) {
        const question = document.querySelector(`input[name='q${i}']:checked`);
        if (question && question.value === correctAnswers[`q${i}`].value) {
          score++;
        }
      }

      document.getElementById("result").innerHTML = `Votre score est de ${score} sur 20.`;
      document.getElementById("correctionBtn").style.display = "block";
    }

    function showCorrection() {
      const correctionDiv = document.getElementById("correction");
      correctionDiv.style.display = "block";
      correctionDiv.innerHTML = "<h2>Correction détaillée</h2>";

      for (let i = 1; i <= 20; i++) {
        const question = document.querySelector(`input[name='q${i}']:checked`);
        const isCorrect = question && question.value === correctAnswers[`q${i}`].value;
        
        const correctionItem = document.createElement("div");
        correctionItem.className = `correction-item ${isCorrect ? 'correct' : 'incorrect'}`;
        correctionItem.innerHTML = `
          <strong>Question ${i}:</strong><br>
          ${isCorrect ? '✅ Correct' : '❌ Incorrect'}<br>
          <strong>Explication:</strong> ${correctAnswers[`q${i}`].explanation}
        `;
        correctionDiv.appendChild(correctionItem);
      }

      correctionDiv.scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>

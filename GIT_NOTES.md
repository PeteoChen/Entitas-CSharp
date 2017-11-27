git update-index --assume-unchanged docs/search/*

git update-index --assume-unchanged docs/*



git ls-files -z Tests/ | xargs -0 git update-index --assume-unchanged

git ls-files -z Readme/ | xargs -0 git update-index --assume-unchanged

git ls-files -z Scripts/ | xargs -0 git update-index --assume-unchanged

git ls-files -z Addons/Entitas.CodeGeneration.CodeGenerator.CLI/ | xargs -0 git update-index --assume-unchanged



git ls-files -z Addons/Entitas.Blueprints/ | xargs -0 git update-index --assume-unchanged
git ls-files -z Addons/Entitas.Blueprints.CodeGeneration.Plugins/ | xargs -0 git update-index --assume-unchanged
git ls-files -z Addons/Entitas.Blueprints.Unity/ | xargs -0 git update-index --assume-unchanged
git ls-files -z Addons/Entitas.Blueprints.Unity.Editor/ | xargs -0 git update-index --assume-unchanged



git update-index --assume-unchanged Addons/Libraries/UnityEditor.dll
git update-index --assume-unchanged Addons/Libraries/UnityEngine.dll

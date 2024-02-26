<h1 align="center">Konichiwaaa!!!~</h1>

<br>
<div align="center">
<img src="https://raw.githubusercontent.com/shir00xgod/shir00xgod/main/75f0aaa07843f3c35917e300e963ce37.gif">
</div>
<br>

<pre>
module Main where

data Person = Person
  { name :: String
  , hobby :: [String]
  , status :: String
  , origin :: String
  , quote :: String
  , socialNetwork :: String
  }

shiro :: Person
shiro = Person
  { name = "Shiro Kageyama"
  , hobby = ["Watching Anime", "Reading Manga", "Playing ML"]
  , status = "Student"
  , origin = "Indonesia"
  , quote = "Being silent doesn't mean being resistant to defecation."
  }

main :: IO ()
main = do
  putStrLn $ "Hello, I'm " ++ name shiro ++ "."
  putStrLn $ "I am a " ++ status shiro ++ " from " ++ origin shiro ++ "."
  putStrLn "My Hobbies include:"
  mapM_ putStrLn $ map (\h -> "- " ++ h) (hobby shiro)
  putStrLn $ "One of my favorite quotes: \"" ++ quote shiro ++ "\""
  putStrLn $ "Let's connect on my social network: " ++ socialNetwork shiro
</pre>

<p align="center">
  <a href="https://open.spotify.com/user/31jq7g4rf7d3u6guzx5uqzor5qrq?si=aUS6tB5iSpmNcOq2kkJDGA" target="_blank"><img src="https://now-playing-on-spotify.vercel.app/api/spotify" alt="Spotify Now Playing" width="350"/></a>
</p>

<div align="center">
  <img align="center" alt="count" src="https://count.getloli.com/get/@:shir00xgod?theme=asoul">
</div>

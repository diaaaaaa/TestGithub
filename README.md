# TestGithub
test
hi farah


def changeUserHash(currentUserId, newHash):
    rows = db.execute("update  users set hash = :newHash where id = :userId",
                      newHash=newHash, userId=currentUserId)
    return rows

